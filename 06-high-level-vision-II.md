# High-Level Vision II: Modularity; fMRI (2021-09-16)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## Why Study Face Perception?

![Grid of diverse human faces](images/pdf1-186.ppm)

- Ubiquitous (fundamental & universal) and highly salient stimulus.
- Key to our survival as social animals.
- A "model system" for high-level perception?
- Applications beyond psychology/neuroscience.

**Some behavioral arguments:**

- Faces catch our attention! (In utero!)
- We see faces though they are noises. (e.g., (◍°∇°◍); man on the moon)
- Faces are processed holistically and configurally. (Holism & configural processing)
  - **The Thatcher effect** or **Thatcher illusion** is a phenomenon where it becomes more difficult to detect local feature changes in an upside-down face, despite identical changes being obvious in an upright face.
  - **Composite face task**: when we combine the top and the bottom half of faces from apparently two different people, they interact with each other to make them seem complete faces.
    - When aligned with different lower halves, it is surprisingly difficult to recognize that the upper regions of the two composites are identical (left-top). However, the illusion-induced interference is greatly diminished when the composites are misaligned (right-top). When composite arrangements are shown upside-down, little illusion-induced interference is seen in either the aligned (left-bottom) or misaligned (right-bottom) conditions.
  - **Part-whole illusion**: in this situation, the shape of the mouth affects the perception of, for example, the nose, the eyes, the eyebrows, the width of the face, etc., suggesting that we perceive faces holistically and configurally.

![A: Thatcher illusion (inverted vs. upright faces); B: Composite illusion; C: Part-whole illusion](images/pdf1-187.ppm)

![Composite face task: aligned vs. misaligned, upright vs. inverted, with RT bar chart](images/pdf1-188.ppm)

- Patients show specific face perception deficits (not in any other type of perception)—**prosopagnosia** (face blindness).
  - When faces are upside down, patient LH can use their spared non-facial processing faculties spared and thus be able to do the task (not as well as the controls but pretty okay). However, when faces are upright, they process the faces as faces and thus perform a lot worse.

![Bar charts: % Correct for patient LH (left) and controls (right) — Upright vs. Inverted face orientation](images/pdf1-189.ppm)

---

## Functional Magnetic Resonance Imaging (fMRI)

![Spatiotemporal scales of neural signals: chart comparing fMRI, EEG, MEG, ECoG, LFP, Optical Imaging, Spikes across time and space axes](images/pdf1-190.jpg)

![Photo of an MRI scanner in a clinical setting](images/pdf1-191.ppm)

- Even though fMRI's spatial and temporal resolution are not as good as other techniques, they are satisfactory enough, and fMRI has the best special coverage—you can measure the entire brain at the same time.

### MRI: Nuclear Magnetic Resonance

- Certain elements can be thought of as properties of magnets.
- In a piece of tissue, we have billions of nuclei of the hydrogen element which have random orientations.
  - In a normal state, if you sum up all their orientations, it is a zero.
  - When you apply a very strong magnetic field (B₀ field), it will align in the parallel or anti-parallel direction.
    - People wearing pacemakers, bracelets, etc. cannot go in.

![Diagrams of proton magnetic moments: random orientation (left), applied B₀ field aligning protons (right)](images/pdf1-192.ppm)

- When a transmit coil sends the right frequencies (rf pulse) of pulse to the protons, they will tip over.
- When removing the pulse, they will all relax back.
- With a receive coil, we can measure the signal (energy) where the protons releasing back from being tipped.

![Transmit and receive coil diagrams with proton tipping and relaxation](images/pdf1-197.ppm)

- In real life, protons happen to be the best thing for MRI, and protons can come in the forms of hydrogen atoms. We happen to have tons of these in the form of H₂O.
  - The figure highlights different parts of tissues with different amount of water.

![MRI brain scans showing axial (left) and sagittal (right) views highlighting tissue contrast](images/pdf1-198.ppm)

  - The NMR properties of hydrogen allow us to see contrast that highlights brain structure.
  - However, we are primarily interested in visualizing brain *function*.

### Functional: Neural Activity → Blood Flow

- The relationship between neural activity and blood flow is complicated and not fully understood.
- Nevertheless, changes in the properties of blood are indicators of neural activity.

![Diagram: Inference of Neural Signal Estimation — showing pathway from Neuronal Activity → Cerebral Blood Flow → Cerebral Blood Volume → Deoxyhemoglobin Concentration → BOLD fMRI Signal](images/pdf1-199.jpg)

- fMRI, rather than measuring tissue contrast, detects changes in the **blood oxygenation level**.
  - **Blood oxygenation level-dependent (BOLD)** signal.
- Hemoglobin has different properties when there are and are not oxygen molecules bounded to it.

![Diagrams: Resting vs. Activated blood vessels (oxygen/hemoglobin); T2* contrast image (functional) and T1 contrast image (structural) brain scans; fMRI signal trace](images/pdf1-200.ppm)

> **T1**: tissue properties; static.
>
> **T2***: change overtime; has something to do with tiny changes in local magnetic fields.

  - Hemoglobin transports more oxygen to a brain area when activated. When hemoglobin turns from oxygenated to deoxygenated, its magnetic signal changes.
  - Therefore, by measuring the signal, we can deduct whether the brain area is at rest or firing.
- The change in neural activity is fast and precise. The change in the blood flow, however, is much slower.

![BOLD response curve over time: initial dip, peak (~5s), post-stimulus undershoot, returning to baseline by ~25s. Stimulus marker at time 0.](images/pdf1-201.ppm)

  - It does not go back to its normal state until about 25 seconds.
  - The **sluggish nature** of the **hemodynamic response function (HRF)** places very important constraints on the experimental design.
  - The initial dip is inconsistent and variable. Its mechanism remains disputed, with the two most popular theories being a) increased early metabolic extraction of blood oxygen, and/or b) increased local cerebral blood volume.
  - The post-stimulus undershoot is variable, most commonly observed in prolonged-stimulus experiments. Its mechanism is disputed, but probably results from both slow recovery of arterial blood volume and a late stimulus- and brain-state-dependent decrease in regional cerebral blood flow.

### fMRI Acquisition

- The subjects can come in for one session or multiple sessions.
- Within one session, there are multiple runs.
- In each single run, we require multiple brain volumes.
  - **Repetition time (TR)**: time required to scan one volume.
- Brains are scanned in (axial) slices.
- There are cubic elements (analogous to a pixel) called **voxels** on each slice.

![fMRI data hierarchy: subjects → sessions → runs → single run → volume → slices → voxel; TR = repetition time = time required to scan one volume](images/pdf1-202.ppm)

![Diagram of a single brain slice showing voxel grid; voxel size example: 3.75 mm × 3.75 mm × 5 mm](images/pdf1-203.ppm)

- fMRI volumes acquired in slices (typically axial).
- A single brain volume takes between 0.75 and 2s to acquire.
- Collect several brain volumes per condition of interest.

### fMRI Analysis: Subtraction Method

- Bold is a *relative* measure → Always require a comparison condition.

![Subtraction method: Hand Clenching minus Rest → Statistical Parameter Map → Overlay onto Anatomical Image (showing Supplementary Motor Area and Primary Motor)](images/pdf1-204.ppm)

---

## Paper 4: Using Human Brain Lesions to Infer Function: A Relic from a Past Era in the fMRI Age? (Using Human Brain Lesions to Infer Brain Function)

### Methods Overview

| Category | Method | Notes |
|----------|--------|-------|
| **Electrophysiology** (Good temporal resolution, Poor spatial resolution) | Event related potential (ERP) | — |
| | Magnetoencephalography (MEG) | — |
| **Functional imaging** (Good spatial resolution, Poor temporal resolution) | Functional magnetic resonance imaging (fMRI) | — |
| | Positron emission tomography (PET) | — |
| | Single proton emission computerized tomography (SPECT) | — |
| **Interference method** | Lesion method | — |
| | Transcranial magnetic stimulation (TMS) | — |

### Group Studies Are Important.

Most individual brain injuries involve many functional modules. It is difficult to precisely identify the region required for a particular function.
- Individual studies cannot / group studies can: precisely identify the brain region required for a specific function.

Single patients might not represent the general population.
- Individual studies cannot / group studies can: represent a broader population.

**Template overlay technique**: as individual brains differ in brain shape, size, and structure, brains from different individuals need to be transformed to a standard stereotaxic space to make group comparisons.
- Due to individual differences in brain shape, size, and structure, a standard stereotaxic space must be established to unify comparisons across individuals.

### The Lesion Method

**Definition**

Lesion: localizing human brain function by studying the correlation between a behavioral disorder and the location of brain injury.
- Correlating behavioral disorders and brain injury location to localize brain function.

**Function**

Is seminal for our understanding of functions as diverse as language, memory, hemispheric specialization, emotion, vision, and motor control.
- Used to understand: language, memory, hemispheric specialization, emotion, vision, motor control.

**Evidence**

| Brain Region | Function | Reference |
|-------------|----------|-----------|
| Left posterior temporal cortex | Language comprehension | (Wernicke) |
| Medial temporal lobe | Encode long-term memory | — |
| Left hemisphere | Superior language and arithmetic skills | (Sperry's work with split brain patients) |
| Right hemisphere | Better spatial skills | (Sperry's work with split brain patients) |
| Amygdala | Recognize whether faces are expressing fear | — |
| Left insula & Basal ganglia | Identify disgust | — |
| Posterior ventral cortex (fusiform gyrus) | Recognize objects | — |
| Posterior dorsal regions | Integrate visual information with goal-directed motor responses | — |

### Limitation of the Lesion Method

Lesion studies assume that discrete anatomical modules deal with different cognitive functions— "modularity" or "localization" assumption. However, many brain functions might be carried out in a distributed manner, with large portions of the brain working in a distributed manner.
- Brain damage assumes different brain modules process different functions. However, brain function is distributed and plastic.

Most brain damage is not limited by the boundaries of the functional modules.
- For example, the middle cerebral artery supplies blood to the frontal, temporal, parietal, and occipital cortices. Disruption of this blood flow usually leads to a wide range of deficits.
- On the other hand, owing to the redundancy of the human brain, small lesions that only partially damage a module might not lead to any obvious behavioral problems.
  - (Even if the modular view holds) sometimes one lesion destroys a large area, and sometimes a small lesion causes no obvious effect.

The brain shows great anatomical differences between individuals, and show plasticity, with different regions changing their functions in response to damage to one area. The plasticity/reconfiguration is helpful for discovery, but makes it difficult to infer the original function of the healthy brain.
- Many individual differences exist: individual differences in brain anatomy are large; recovery from injury due to neural plasticity also varies.

Lesion faces differential vulnerability: some areas are particularly likely to be damaged by stroke. This makes it difficult to interpret lesion overlay plots—is this region specially involved in this behavior or it is simply a commonly damaged zone?
- "Differential vulnerability": brain injury sites are not randomly distributed, making lesion overlay maps difficult to interpret.

Brain regions can be disabled but intact after injury (such as impaired by disconnection or information processing).
- If we test the patients in the acute stage of their illness, we will not be able to accurately identify all the brain regions that are impaired.
- However, if we wait for these initial problems to resolve, the problems associated with brain plasticity will become more pronounced.
  - Brain areas may lose function while remaining structurally intact (e.g., disconnection / damage to information processing pathways).
  - In the acute stage, it is not possible to identify all affected regions.
  - If we wait, the issue of plasticity becomes more pronounced.

Lesion cannot give us ideas of the temporal sequence of information processing which is crucial for understanding both the stages of processing and the roles of the feedback.
- Difficult to understand temporal sequence; cannot provide information about processing stages or feedback roles.

### Benefits of fMRI

We can look at the brain of healthy people.
- Broader subject selection: healthy populations can be studied.

We can eliminate the problem of differential vulnerability, plasticity, and disconnection that are associated with the lesion method.
- Addresses the limitations of brain damage: "differential vulnerability", neural plasticity, and disconnection.

fMRI offers better temporal resolution than lesion.
- Better temporal resolution.

fMRI can show every part of the network that is involved in a task or a behavior.
- Shows every part of the network involved in a task/behavior.

### Limitations of fMRI

It is not clear whether this region is necessary to perform this task.
- Not clearly proven that a region is necessary for the task.

It is even possible that some activated areas have no direct roles in information processing, but are activated because their connection regions are required for the task. (e.g., bilateral activation of language)
- Areas may not directly participate in task processing but are activated because their connected regions are activated. (e.g., bilateral activation due to language processing)

The fMRI technique cannot detect the possible contributions of the regions that are constantly active, regardless of the task.
- If a region is continuously activated (no change in difference value), fMRI cannot detect it.
