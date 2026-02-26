# Module 2: Perception

---

## High-level Vision I: How Do We Perceive? (2021-09-14)

### Sensation vs. Perception

> **Sensation**: the process by which the nervous system receives and represents physical stimulus energy.

> **Perception**: the process of organizing, interpreting, and consciously experiencing signals from our environment.

- Sensation = receiving and encoding information
- Perception = interpreting and experiencing that information

---

### Sensory Systems

Some of the problems a sensory system has to solve:

1. **Differentiate between physical stimuli**
   - Different types of physical stimuli activate different types of specialized receptors
     - Each receptor responds to one type of stimulus energy:
       - Rods & Cones in retina → Light
       - Taste buds on tongue → Chemicals
   - Different sensations are carried to the brain via different pathways
   - Different sensations are processed by different parts of the brain

2. **Localize a physical stimulus**
   - How do we localize stimuli in space?
     - **Spatial receptive fields**: receptors and neurons respond to sensations in a specific area of space
       - Touch receptors
       - Photoreceptors
     - Receptive fields have a center and a size — the smaller the receptive field, the higher the acuity

3. **Represent the intensity of a physical stimulus**

---

### Perception as an Inference

> **Inference**: a conclusion reached on the basis of evidence and reasoning.

> "Seeing is not a direct apprehension of reality, as we often like to pretend. Quite the contrary: seeing is an inference from incomplete information." — E.T. Jaynes

- When we perceive, we combine evidence (incomplete information) with our **prior knowledge of the world**
  - Example: the directionality of the visual pathway — there are more fibers carrying information *against* the flow of information (in the reverse direction), which is probably because the cortex influences lower-level regions and modifies the information being stored and transmitted from the retina to the cortex

---

### Dorsal & Ventral Streams

**What information is processed in each stream?**

| Stream | Function | Alternative Framing |
|--------|----------|---------------------|
| **Ventral stream** | Complex object information | "Vision for perception" (Goodale & Milner, 1992) |
| **Dorsal stream** | Spatial information, location, movement | "Vision for action" (Goodale & Milner, 1992) |

- **What vs. Where** (Ungerleider & Mishkin, 1982)

**Evidence from brain damage:**

- **Hemispatial neglect**: damage to parietal lobe (dorsal stream)
- **Patient DF**: damage to ventral stream
  - Perceptual orientation matching task (understanding orientation) — impaired
  - Putting a card in a slot (action-based task) — relatively preserved

**Evidence from neurophysiological data — dissociation of information processing:**

- **Middle temporal area (area MT)**: motion direction preference
- **Inferior temporal cortex (IT cortex)**: processes cortices and faces
  - Eyes are important, but the **holistic configuration** is more critical — no firing for hands (familiarity is not a factor)
  - Properties of IT neurons:
    - Preference for faces and face-like objects
    - **Size invariance**
    - **Position invariance**
    - Category vs. Token/Exemplar processing

---

### Paper 5: Separate Visual Pathways for Perception and Action

**Original framework (Ungerleider & Mishkin, 1982):**

| Stream | Pathway | Function | Lesion Effect |
|--------|---------|----------|---------------|
| **Ventral stream** | Striate cortex → Inferotemporal cortex | Objects' qualities | Impairs visual pattern discrimination and recognition |
| **Dorsal stream** | Striate cortex → Posterior parietal cortex | Objects' spatial location | Impairs solving landmark tasks |

**Revised framework (Goodale & Milner, 1992):**

Temporal and parietal lobes can both be involved in shape analysis, but are associated with different strategies:

| Stream | Function | Reference Frame | Elaboration |
|--------|----------|-----------------|-------------|
| **Ventral stream** | Vision for perception: perceptual identification of objects | Object-centered | Consistencies of shape, size, color, lightness, and location must be maintained across different viewing conditions |
| **Dorsal stream** | Vision for action: mediates sensorimotor transformations for visually guided actions directed at objects | Viewer-centered | Location of the object; object's particular disposition and motion with respect to the viewer (egocentric coordinates) |

---

## High-level Vision II: Modularity; fMRI (2021-09-16)

### Why Study Face Perception?

- Ubiquitous (fundamental and universal) and highly salient stimulus
- Key to our survival as social animals
- A "model system" for high-level perception
- Applications beyond psychology and neuroscience

---

### Behavioral Arguments for Special Face Processing

- Faces catch our attention — even **in utero**
- We see faces in noise (e.g., emoticons; the man on the moon — **pareidolia**)
- Faces are processed **holistically** and **configurally**:
  - **The Thatcher Effect**: it becomes more difficult to detect local feature changes in an upside-down face, despite identical changes being obvious in an upright face
  - **Composite face task**: when the top and bottom halves of two different people's faces are aligned, they interact to create the perception of a complete new face — making it surprisingly difficult to recognize that the upper regions are identical. The illusion is greatly diminished when the halves are misaligned, and nearly absent when shown upside-down
  - **Part-whole illusion**: the shape of the mouth affects the perception of the nose, eyes, eyebrows, face width, etc., suggesting holistic and configural processing
  - **Prosopagnosia (face blindness)**: patients show specific face perception deficits — patient LH can use spared non-facial processing when faces are upside-down and performs reasonably, but performs much worse with upright faces (processed as faces)

---

### Functional Magnetic Resonance Imaging (fMRI)

Although fMRI's spatial and temporal resolution are not as good as some other techniques, its **spatial coverage** is superior — the entire brain can be measured simultaneously.

#### How MRI Works

- **Nuclear magnetic resonance (NMR)**: certain elements behave like magnets
- Tissue contains billions of **hydrogen nuclei** with normally random orientations
  - Normal state: sum of orientations = zero
  - Under a strong magnetic field (**B0 field**): protons align in parallel or anti-parallel directions
- A transmit coil sends a **radiofrequency (RF) pulse** at the right frequency → protons tip over
- When the pulse is removed, protons **relax back** and release energy, which is measured by a receive coil
- **Protons in H₂O** are ideal for MRI:
  - Different amounts of water in different tissues create contrast, highlighting brain structure
  - NMR properties of hydrogen allow visualization of brain anatomy

#### From MRI to fMRI: Neural Activity → Blood Flow

- The relationship between neural activity and blood flow is **complex and not fully understood**
- Changes in blood properties are used as **indicators of neural activity**
- fMRI detects changes in blood oxygenation: the **Blood Oxygenation Level-Dependent (BOLD) signal**
- Hemoglobin has different magnetic properties when oxygenated vs. deoxygenated:
  - **T1**: tissue properties; static
  - **T2\***: changes over time; related to tiny changes in local magnetic fields
- More oxygen is delivered to **active brain areas** → hemoglobin shifts from oxygenated to deoxygenated → magnetic signal changes

#### The Hemodynamic Response Function (HRF)

- Neural activity changes are **fast and precise**; blood flow changes are **much slower**
- Blood flow does not return to baseline until approximately **25 seconds** after stimulation
- The **sluggish HRF constrains experimental design**
- The **initial dip**: inconsistent — disputed theories:
  - Increased early metabolic extraction
  - Increased local cerebral blood volume
- The **post-stimulus undershoot**: variable; results from slow recovery of arterial blood volume and late decrease in regional cerebral blood flow

#### fMRI Acquisition

- Hierarchy: **Sessions → Runs → Brain volumes**
- **Repetition time (TR)**: time to scan one full brain volume
- Scanned in **axial slices** with voxels
- Single volume acquisition time: **0.75 to 2 seconds**
- Multiple volumes collected per condition

#### fMRI Analysis: Subtraction Method

- BOLD is a **relative measure** — always requires a comparison condition

---

### Paper 4: Using Human Brain Lesions to Infer Function: A Relic from a Past Era in the fMRI Age?

**Comparison of neuroimaging methods:**

| Method | Temporal Resolution | Spatial Resolution |
|--------|--------------------|--------------------|
| Electrophysiology (ERP, MEG) | Good | Poor |
| Functional imaging (fMRI, PET, SPECT) | Poor | Good |
| Interference methods (Lesion, TMS) | — | — |

**Why group studies are important:**
- Individual brain injuries involve many functional modules — difficult to precisely identify the region required for a particular function
- Single patients may not represent the general population
- **Template overlay technique**: brains from different individuals must be transformed to a standard **stereotaxic space** for group comparisons

#### The Lesion Method

> **Definition**: localizing human brain function by studying the correlation between a behavioral disorder and the location of brain injury.

**Key functional evidence established by the lesion method:**

| Brain Region | Function |
|-------------|----------|
| Left posterior temporal cortex | Language comprehension (Wernicke) |
| Medial temporal lobe | Encoding long-term memory |
| Left hemisphere | Superior language and arithmetic skills |
| Right hemisphere | Better spatial skills (Sperry's split-brain patients) |
| Amygdala | Recognizing fear expressions in faces |
| Left insula & Basal ganglia | Identifying disgust |
| Posterior ventral cortex (fusiform gyrus) | Recognizing objects |
| Posterior dorsal regions | Integrating visual information with goal-directed motor responses |

#### Limitations of the Lesion Method

- Assumes **discrete anatomical modules** handle different cognitive functions ("modularity"/"localization" assumption) — but many brain functions may be distributed
- Most brain damage does not respect functional module boundaries (e.g., the middle cerebral artery supplies frontal, temporal, parietal, and occipital cortices)
- Brain **redundancy** means small, partial lesions may not produce obvious behavioral deficits
- **Individual anatomical variation** and **brain plasticity** complicate interpretation
- **Differential vulnerability**: some areas are disproportionately likely to be damaged by stroke, making lesion overlay plots hard to interpret
- Brain regions can be functionally disabled while structurally intact after injury (**impaired by disconnection**)
- Cannot reveal the **temporal sequence** of information processing

#### Benefits of fMRI over the Lesion Method

- Can be used with **healthy participants**
- Eliminates problems of differential vulnerability, plasticity, and disconnection
- Better temporal resolution than lesion studies
- Can reveal **every part of the network** involved in a task

#### Limitations of fMRI

- Cannot confirm whether an activated region is **necessary** for the task
- Some activated areas may have no direct role but co-activate because connected regions are required
- Cannot detect contributions of **constantly active regions**

---

### Paper 6: The Fusiform Face Area: A Module in Human Extrastriate Cortex Specialized for Face Perception

**Big aim**: test the selectivity of face processing and find evidence for the face module.

**Why only right-handed participants were used:**
1. Left-handed individuals make up a small portion of the population
2. Left-handers show less consistent lateralization

#### Experimental Design (fMRI)

**Block design**: does not focus on individual objects or faces; prolonged stimulation produces a sustained signal increase.

#### Methods and Rationale

| Experimental Step | Purpose |
|---|---|
| Part I: (1) Anatomically localize candidate "face areas" within individual subjects; (2) determine if regions are activated consistently; (3) specify precisely the voxels in each subject's ROI | Search for any occipitotemporal areas specialized for face perception |
| Part II: Intact two-tone faces vs. Scrambled two-tone faces; Front-view faces vs. Front-view houses | Rule out low-level feature confounds; rule out exemplar/subordinate-level processing confounds |
| Part III: 3/4-view faces vs. Human hands | (1) Test generalization to different viewpoints; (2) control for hair features; (3) test whether the region responds to any animate/human body part |
| Same as Part III but with a "1-back" memory task | Test whether the face condition engages more attention than the non-face condition |

#### Critiques

**Faces vs. Houses comparison:**
1. Faces have strong shape consistency (averaged faces are still faces); houses do not
2. We are much better at **individuating faces** than houses — the failure of the "face area" to activate during house individuation does not necessarily prove people fail to individuate faces
3. The FFA may simply be an **area of expertise**, not a face-specific module

**1-back task critique:** Task difficulty does not necessarily correlate with attentional engagement.

---

## fMRI Demonstration (2021-09-23)

*(No lecture notes — in-class search for face modules in the brain)*

---

## High-level Vision III: Faces (2021-09-28)

### Composite Face Task (Revisited)

- The key manipulation is **congruency**:
  - Participants should perform **better in congruent** than incongruent conditions because faces are processed holistically
  - In **incongruent** conditions, part of the face is the same when the correct response is "different," and vice versa — holistic processing interferes with part-based judgments

---

### Block vs. Event-Related fMRI Design

| Design | Strengths | Weaknesses |
|--------|-----------|------------|
| **Block design** | Most statistically powerful; simple | Serious psychological limitations (habituation to stimuli) |
| **Slow event-related design** | More flexible; avoids habituation | Less statistically powerful; boring; inefficient |
| **Rapid event-related design** | Good tradeoff between statistical power and psychological validity | — |

---

### Beyond the FFA

- Multiple **face-responsive areas** exist in the ventral visual stream (occipital and temporal cortex)
- This organization is relatively **conserved across humans and macaques**

---

### Detection or Recognition?

- Evidence for **tuning to individual faces** in humans at the voxel level (population-level face coding)

---

### Visual Agnosia

> **Apperceptive agnosia**: failure of recognition due to deficits in early stages of perceptual processing.
- Some low-level sensory functions and feature identification are spared, as is abstract understanding of visual properties

> **Associative agnosia**: failure of recognition despite no apparent deficit in perception.
- "The purest form as a normal percept that has somehow been stripped of meaning"
- **Counterargument**: the perception of many patients is unlikely to be truly normal — despite producing high-fidelity drawings, many patients copy in a "slavish," "line-by-line" manner, exceedingly slowly

---

## High-level Vision IV: Faces, Objects, and Modules Revisited (2021-09-30)

### Prosopagnosia Revisited

- Prosopagnosics display an **inverted face inversion effect** (unlike typical observers)
- Relationship between prosopagnosia and occipitotemporal face-processing regions remains unclear
- People with **developmental prosopagnosia** may have reduced density of the **inferior longitudinal fasciculus**
- Prosopagnosia does not provide much insight into the neural basis of typical face processing

---

### Causal Evidence for Face-Selective Regions

- Patients with **epilepsy** experience light flashes due to abnormal activation of visual neurons
- Researchers use intracranial electrodes to stimulate the visual system directly
- Key takeaways from electrical stimulation studies:
  - Electrodes alter visual perception broadly (light flashes, metamorphosis of faces, objects, words)
  - Changes are **not random** — they show specific consistencies (shape changes/stretches)
  - One patient reported that a face changed into someone previously seen, implicating both recognition and memory
  - **Spontaneous report** methodology is valuable for drawing convincing conclusions

---

### Beyond Face Modules: The Ventral Temporal Map

| Abbreviation | Full Name | Location | Function |
|---|---|---|---|
| **FFA** | Fusiform Face Area | IT cortex, fusiform gyrus (BA 37) | Face recognition |
| **EBA** | Extrastriate Body Area | Anterior to V1/striate cortex | Visual perception of the body and body parts |
| **PPA** | Parahippocampal Place Area | Medially in inferior temporo-occipital cortex | Encoding and recognition of environmental scenes |
| **VWFA** | Visual Word Form Area | Left fusiform gyrus and surrounding cortex | Word recognition; may also process meaning |
| **LO** | Lateral Occipital | Lateral occipital cortex (general) | Visual object perception |

**Potential problem with strict modularity:**
- We can perceive an infinite number of things — impossible to have infinitely many modules
  - **Counterargument**: one doesn't need infinite modules — just modules for the most important and frequently encountered categories

---

### Grandmother Cells

- Individual neurons in the human **medial temporal lobe** responded selectively to images *and names* of specific individuals
- Evidence for modules taken to an extreme? (A particular neuron for Jennifer Aniston — responds to portraits, caricatures, and written names)
- **What is their function?**
  - Perception? Unlikely — medial temporal lobe is not a perceptual region
  - Recognition? Too slow for real-time recognition
  - New/old long-term memory encoding? Possibly
- **Counterargument — Face PC space**: the visual system of the monkey uses a **face principal component (PC) code** for perceptual analysis. A single grandmother cell could not uniquely represent an individual face, because an infinite number of faces can share the same value along any single axis

---

### A Non-Modular Account: Distributed Representation

- The **pattern of activity across ventral temporal cortex** predicted object category
- High correlations between odd and even runs of the same category; unrelated correlations across different categories
- Critically, this held even when the most modular voxels were removed — **96% accuracy** was maintained
  - Even without the FFA, the distributed pattern was similar
  - Supports **distributed processing across cortex**

---

### Interim Summary: Modular vs. Distributed Processing

- Strong empirical evidence exists for **both** perceptual modules in IT and distributed processing across ventral temporal cortex

---

### A Reconciliation?

- "Modular" regions process many kinds of stimuli, even if they respond preferentially to one class
- **"Modularity" arises due to specific computations** rather than because a region processes specific types of information

---

### Faces vs. Words: A Case Study in Competing Modularity

- Strong evidence for modular processing in **both** domains
- Similar computational demands? But different evolutionary and developmental timescales
- **Lateralization of face processing** develops relatively late (~10 years old, possibly up to age 30)
- **Lateralization of word processing** emerges around age 10
- Reading competence is **correlated with face lateralization**
- Face and word "modularity" may emerge as a result of **competition for processing resources**
- Theory: the module reflects the **type of computation** associated with certain object categories, not the category itself

---

### A Model for Face Recognition: Axis-Based Coding

- Face-sensitive neurons in macaques are tuned to different **face "axes"** rather than to individual faces
  - From 200 neurons' population activity, experimenters could predict which face a monkey was viewing
  - Neurons respond equally to two different faces that share the same value on a particular axis
  - Neurons are tuned to **multiple axes**, not to specific facial identities
- Any face can be described as a combination of values along approximately **50 axes**
- This supports a **population code** model of face representation, consistent with the distributed processing account
