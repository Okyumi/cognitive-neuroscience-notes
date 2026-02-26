# Module 3: Attention & Working Memory

---

## Lecture 1: Attention I — Cognitive Models; M/EEG

*(Date: 2021-10-07)*

### What Is Attention?

> "Everyone knows what attention is. It is the taking possession by the mind, in clear and vivid form, of one out of what seem several possible objects or trains of thought. It implies withdrawal from some things in order to deal effectively with others." — William James, 1890

**Attention** is the ability to focus our processing resources on a subset of our internal or external environment.

### Change Blindness

**Change blindness** is a phenomenon of visual perception that occurs when a stimulus undergoes a change without being noticed by its observer. The effect has been produced by changing images displayed on screen as well as changing people and objects in an individual's environment. Attention manages such oversights by narrowing down the field and allowing us to focus processing resources on a subset of the environment.

### Taxonomy of Attention

**What types of things are we able to pay attention to?**
- The ability to focus processing resources on a subset of our internal or external environment.
  - Vision, sound, taste, touch, feelings, thoughts, memories…

**What drives our attention?**
- **Exogenous attention**: stimulus-driven attention (bottom-up).
  - Directed to salient information in our environment.
- **Endogenous attention**: goal-driven attention (top-down).
  - Directed to information relevant to our goals.
- Both forms of visual attention are **independent of eye movements** (important confound to consider).
- Neither form is inherently tied to early or late selection (elaborated below).

### Attention in Two Parts

- **Part I**: How does attention change how we process information?
  - What are the consequences of attention for behavior and sensory/perceptual processing?
- **Part II**: How do we select what we want to attend to in our environment?
  - Endogenous (goal-driven) attention.

---

### Part I: Consequences of Attention

In a classic paradigm, participants are cued with an arrow indicating which side to direct their attention to while keeping their gaze fixed. This **dissociates attention from gaze direction**, holding sensory input constant while varying the focus of attention.

> **Key design principle**: "Fixing the stimuli and changing the attention" is preferable to "fixing attention and changing the stimuli" because the sensory inputs remain identical.

**Behavioral consequences of directing attention:**
- Better **detection**: was a dot present or not?
- Better **discrimination**: was a line tilted left or right?

**Important implication**: We have *worse* detection and discrimination for **unattended** information — a push/pull mechanism (as William James described).

> **Thought question**: Can we conclude from these data alone that unattended processing is worse?
> No. A neutral baseline condition (attention directed to center) is required to determine whether attended is better, unattended is worse, or both.

---

### Local Field Potential (LFP) and M/EEG

> **Local Field Potential (LFP)**: A measure of summed post-synaptic potentials from populations of neurons. LFP amplitude and frequency tell us about the amount of coordinated activity in a population of neurons.

#### EEG (Electroencephalography)

**EEG** works by placing electrodes on the surface of the scalp. The LFP generated at the brain's surface — despite being filtered and attenuated by skin and tissue — can still be measured by sensitive electrodes. Neural signals are very weak, so they can only be measured when large numbers of neurons fire in coordination. There is also a **spatial filter effect**: the signal spreads across the entire skull, making it impossible to determine where it arose from.

- Metal electrodes are attached to an elastic cap; conducting gel connects electrodes to the scalp.
- EEG works best for neurons aligned **perpendicular** to the scalp.

| Aspect | EEG |
|--------|-----|
| **Temporal resolution** | Excellent |
| **Spatial resolution** | Poor |
| **Cost** | Relatively cheap (~$30–40k setup; minimal per-subject cost) |
| **Limitation** | Cannot solve the inverse problem: you can predict scalp activity from a source, but not the source from scalp activity (mathematically impossible) |

#### MEG (Magnetoencephalography)

When there is an electrical current, a corresponding magnetic field is generated. **MEG** measures the magnetic field produced by these electrical currents. The sensors are located outside the skull, housed in a dewar filled with liquid helium. SQUIDs (Superconducting Quantum Interference Devices) detect fluctuations in the magnetic field. MEG can better pick up sources from different brain regions that are oriented differently with respect to the scalp, providing complementary information to EEG.

| Aspect | MEG |
|--------|-----|
| **Temporal resolution** | Excellent |
| **Spatial resolution** | Moderate (source reconstruction possible) |
| **Cost** | Expensive (liquid helium replacement) |

---

### Extracting Meaningful Information from M/EEG

Two main approaches:

#### 1. Event-Related Averaging

The goal is to measure the brain's response to a particular stimulus or operation. This signal is always embedded in **noise** (anything we are not interested in measuring).

**How to remove noise:**
- Eliminate outside interference (electrically shielded rooms).
- Careful experimental design.
- **Signal averaging**: noise is random and cancels out when averaging across many trials.

#### 2. Time-Frequency Decomposition

Any continuous signal that varies in time can be thought of as a **combination of sinusoids**. The signal can be decomposed into these sinusoids and each component studied as a function of mental state.

**M/EEG frequency bands** (physiologically meaningful):
- **Gamma**: associated with action potentials.
- **Alpha**: associated with inhibitory processing.

---

## Lecture 2: Discussion of Worden et al.; M/EEG Demonstration

*(Date: 2021-10-12)*

### Paper 7: Anticipatory Biasing of Visuospatial Attention Indexed by Retinotopically Specific α-Band EEG Increases over Occipital Cortex

*(Worden et al.)*

**Context:**
- **Covert attention** = endogenous attention (willfully directed; no salient stimulus).
- Purpose: process relevant information and filter out irrelevant information.
- The study focuses on the **delay period** — alpha activity before the onset of the stimulus.

**Core concept — Gating effect**: Alpha oscillations serve as a gate controlling which sensory information is processed more or less (allowing some things to pass through while suppressing others).

**Key data question**: Where do the alpha waves come from?
- The data concern the **amplitude** of the alpha oscillations, not simply the presence of brain activity.

**Key findings:** Sustained focal increases in **alpha-band** activity were seen over occipital cortex **contralateral** to the ignored location (ipsilateral to the cued direction of attention). This suggests that alpha increases reflect active **suppression** of irrelevant spatial locations.

---

## Lecture 3: Attention II–III — Neural Models, Control of Attention; Eye Tracking

*(Dates: 2021-10-14 & 2021-10-26)*

### What Is the Unit of Selection?

What aspect of attended information are we actually paying attention to? The answer is: **any of them, depending on our goals.**

| Unit | Description |
|------|-------------|
| **Location** | Spatial position in the visual field |
| **Feature** | A specific dimension (e.g., color, motion) |
| **Object** | The entire object as a unit |

### Objects as the Unit of Selection

**Experimental paradigm**: A house and a face overlaid with each other (50/50). Two types of stimuli (houses moving/faces static; faces moving/houses static) and two attention conditions (attend to motion; attend to position).

**Result**: Increased BOLD signal in object-selective areas (**FFA** for faces; **PPA** for places) when a *feature* of that object was attended — even though the face/house identity was irrelevant to the task.

> **Conclusion**: Enhanced processing due to attention **spreads** from the attended feature to other attributes of the attended object. ("When you pay attention to one feature of an object, other parts come along for free.")

**Critique**: BOLD activity in object-selective areas does not necessarily mean *attention* per se. The concern is **reverse inference** — inferring a cognitive state from brain activity. This is avoided by predicting beforehand which area should be active and testing that prediction.

### Interim Summary of Attention

- Attention can operate on different dimensions: **location, feature, object**.
- Attention boosts behavioral performance: increases accuracy, decreases reaction time, decreases detection threshold. (Equivalent to presenting a brighter or more tilted stimulus.)
- One mechanism: **gating/selecting sensory processing via alpha oscillations** — enhancement or inhibition relative to the neural baseline.
- **Early vs. late selection debate**:
  - The **cocktail party effect** (filtering out irrelevant voices) could reflect either early (sensory/perceptual) or late (decision-making) selection.
  - "Breakthrough effects" (hearing your own name across a noisy room) suggest late selection: all sensory/perceptual information gets in, then a decision is made.
  - fMRI is not ideal for resolving this due to poor temporal resolution.

### Neural Evidence for Early Selection (EEG)

**Approach**: Measure neural response to faces using EEG; observe when this response is modulated by attention.

**N170**: A negative deflection occurring approximately 170 ms after face presentation. N170 is modulated by "faceness" — a face that is recognized or not will still elicit N170 (analogous to the FFA, but as a temporal signature rather than a spatial region).

**Key finding**: N170 is **modulated by attention to faces** at the early stages of sensation/perception — evidence for early selection. Using composite images and a paradigm that fixes the stimuli while varying attention (same sensory inputs), attention modulation of N170 was demonstrated.

---

### Part II: The Oculomotor System and Control of Attention

There is a **high degree of overlap** between the system for controlling attention and the system for controlling eye movements.

#### Parkinson's Disease (PD) and the Oculomotor System

PD disrupts oculomotor function: slow saccades, more jumps rather than smooth movements. **Deep brain stimulation (DBS)** — implanting and stimulating electrodes — can largely alleviate PD symptoms.

#### FEF and the Control of Attention

**FEF** (**Frontal Eye Fields**) play a key role in controlling attention independent of eye movements.

**Experimental procedure**: Record from V4 neurons; stimulate FEF neurons with overlapping receptive fields.
- Stimulating the FEF neuron causes an eye movement to a region of space.
- V4 and FEF neurons are paired by matching: visual receptive field of V4 and saccade field of FEF.

**Key manipulation**: Microstimulate the FEF neuron at a **subthreshold level** (too weak to trigger a saccade). Eyes remain still.

**Result**: V4 neuron activity increased following FEF microstimulation — despite no eye movement occurring.

> **Conclusion**: Subthreshold microstimulation of FEF is sufficient to enhance activity in the corresponding V4 neuron, similar to the effect of endogenous attention. This provides **a plausible mechanism for how attention gets shifted** and is evidence for **early selection** (occurring at the sensory-perceptual stage).

---

### Eye Tracking

- **Monkeys**: a coil is surgically implanted subconjunctivally on the sclera.
- **Humans**: an infrared camera illuminates the eye and software tracks pupil position.
- A calibration process maps physical screen distance to the tracking system.

---

### Paper 8: Top-Down Attention Selection is Fine-Grained

*(Navalpakkam & Itti; discussed 2021-10-28)*

**Goal**: Characterize the granularity of top-down attention signals.
- Top-down = endogenous attention; bottom-up = exogenous attention.
- **Granularity** encompasses: (1) precision; (2) the dimension/feature (general vs. specific).

**Task**: 25 Ls on the screen; find and report the number of targets (upside-down L). Targets differ from distractors in a single feature dimension (e.g., luminance, size, saturation). Within each dimension, three intervals (e.g., low/mid/high luminance).

- **Coarse guidance** would boost all intervals equally.
- **Fine-grained guidance** would boost only the target interval.

**Measure**: Number of fixations on the target feature interval (eye tracking); reaction time (less informative).

**Key result**: Fixation data suggested fine-grained, specific boosting of one feature interval rather than all — evidence that top-down attention is fine-grained rather than coarse.

**The linear separability problem**: When testing whether attention is selective at the mid-interval (rather than low or high), one cannot simply boost high or low. The paradigm specifically tests whether the mid-level interval can be independently targeted.

#### Critiques

- **Duration and trial count**: 3 days of testing with only 200 trials/hour is very slow; may introduce fatigue or strategy shifts.
- **Counterbalancing**: Order of conditions was not clearly counterbalanced (possible confound).
- **Target location**: Not explicitly stated whether locations were randomized.
- **Speed-accuracy trade-off**: Not addressed. In this type of task, only when both speed *and* accuracy improve together can we attribute it to attention or WM; otherwise, participants may simply shift strategy.
- **Sample size**: Only 3 subjects (though somewhat acceptable for low-level processing that is unlikely to vary across populations).
- **Shape confound**: The shape of the target (upside-down L) differs from distractors — shape is a potential confound, independent of the tested dimension (e.g., luminance). Could be fixed by also including upside-down Ls in non-target feature intervals.
- **Search type**: Low fixation counts suggest a possibly **parallel** rather than serial search, making it less clear that active attention guidance is driving results.

**Parallel vs. serial search**:
- **Parallel search**: The whole field is processed at once; reaction time does not increase with the number of items.
- **Serial search**: Items are searched one at a time; reaction time increases with item count.

---

## Lecture 4: Working Memory I — Cognitive Models

*(Dates: 2021-10-26 & 2021-11-02)*

### What Is Working Memory?

> **Working memory (WM)**: The ability to actively represent information over brief intervals when it is no longer available in our environment.

- A core cognitive function that facilitates reasoning, planning, and communication.
- Analogy: an **Etch-a-Sketch board** — fragile, limited in capacity and resolution.

**Key distinctions:**
- **Active representation**: requires repeated rehearsal (active), in contrast to passive storage (LTM).
- **Format**: virtually any perceivable content — visual, auditory, olfactory, emotional, etc.
- **Temporal scale**: decays over seconds. Some memories transform into LTM; there is no sharp temporal boundary between WM and LTM.

### Why Study Working Memory?

- **Basic science**: WM is a core cognitive function and may serve as a model system for understanding higher-order cognition more broadly.
- **Clinical relevance**: WM impairments are found in schizophrenia, depression, ADHD, aging, traumatic brain injury, multiple sclerosis, stroke, and other conditions.
- **Sociological relevance**: WM ability is related to socioeconomic status (SES) and scholastic outcomes. Brain training programs are fundamentally WM training.

### Key Questions in WM

**Behavioral:**
- How much information can we hold in WM? (**Capacity**)
- What is the **format** of things held in WM?
- Are all things in WM equal?

**Neural:**
- How does information **persist** over time?
- What are the neural computations underlying active storage?

---

### WM vs. Short-Term Memory

Some researchers draw important distinctions; others (including this course's professor) tend not to:
- **Short-term memory**: retaining information (more passive).
- **Working memory**: manipulating information on top of storage (more active).

### The Hippocampus and WM

Can we say the hippocampus plays a role in LTM but not WM?
- **Medial temporal lobe (MTL)** structures including the hippocampus are critical for LTM, but their role in WM is less central.
- However, evidence suggests nuance:
  - Patients with MTL damage show subtle but significant WM deficits.
  - Humans with implanted electrodes (due to epilepsy) show MTL neuron activation during WM tasks.
  - Therefore, the hippocampus is involved in WM to *some* degree, though the exact circumstances and role remain an open question.
- The neural bases of LTM and WM are distinct at the level of individual neurons, but the regional distinctions are less clean.

---

### What Is the Capacity of WM?

#### Span Tasks

**Simple span**:
- Participants see a sample display (shapes/letters), which disappears, followed by a 2-second delay. A probe appears and participants indicate whether it matches the sample.
- Advantages: easy to analyze; allows study of how items are stored.
- **Phonological loop**: Evidence from recall errors suggests letters presented visually may be acoustically coded in WM — participants more often substitute acoustically similar letters (e.g., T for G) than visually similar ones (e.g., Q for G). This was the first evidence for an acoustic rehearsal code.

**Complex span**:
- Participants see a series of equations, judge their correctness, and must also memorize a letter appearing between each equation. Typical span: 4–7 items.
- Higher **ecological validity** (closer to real life), and more strongly correlated with IQ, SES, and dopamine status.

#### Span and Dopamine

**Dopamine (DA)** is an important neurotransmitter implicated in reward and learning; DA dysfunction is found in schizophrenia, PD, and addiction.

**Inverted-U relationship (the Goldilocks effect)**: Either too little or too much dopamine leads to low cognitive ability; there is an optimal level. This pattern relates to WM span/capacity.
- Administering dopamine pushes people along this curve:
  - Giving dopamine to people with *low* WM span **improves** their span.
  - Giving dopamine to people with *high* WM span **worsens** their span.
- The effects of dopamine-manipulating drugs depend on the individual's starting point.
- Certain genes predict where people fall on the curve (genotyping is possible).
- In females, position on the curve varies with the menstrual cycle (estrogen has effects on neuronal morphology).

---

### Simple Span Revisited: Measuring WM Precision

A key limitation of binary span tasks: they only give a yes/no answer about whether recall was correct.

**Modification — color wheel task**: Instead of a binary match/non-match response, participants reproduce a color on a continuous wheel. This yields a **continuous measure of WM precision** (angular error).
- Confounds: perception differences, vision quality, motor difficulties — controlled by a baseline trial without a delay.
- The better the WM, the narrower the distribution of errors around the correct value.

**Two competing models of WM capacity:**
- **Resource model** (continuous): WM resources are a continuous pool divided among items; more items = fewer resources per item = lower precision.
- **Slots model** (discrete): WM has a fixed number of discrete "slots"; items fit perfectly until slots are full.

---

### How Do We Study WM and the Brain?

**Delay tasks**: Segregate the three stages:
1. **Encoding**: stimulus is presented.
2. **Maintenance**: delay period (stimulus absent).
3. **Retrieval/Response**: probe and response.

Most research focuses on the **maintenance** phase, as delay tasks allow isolation of neural activity associated with each sub-component.

**Delay period activity**: Neural activity that persists during the delay of a WM delay task.

**The Oculomotor Delayed Response (ODR) task**:
- Focuses on the **principal sulcus** (dorsolateral prefrontal cortex, DLPFC).
- Neuron fires at baseline level → firing remains **elevated throughout the entire delay** → fires during response → returns to pre-trial baseline.
- This persistent elevated firing is the hallmark neural signature of WM maintenance.

**Observed in the human PFC with fMRI**:
- Critique: delay-period activation is not necessarily pure WM maintenance — it may be contaminated by other factors (e.g., attention, task rule maintenance).

---

### Labeled Line Theory vs. Population Coding

#### Labeled Line Theory

> A group of neurons completing one general function is called a **dedicated circuit**, often serving one specific sensory modality.

**Premises:**
- Individual primary afferent fibers carry information from a single type of receptor.
- Pathways carrying sensory information centrally are therefore specific ("labeled lines").

**Conclusions:**
- The brain associates a specific modality with a signal coming from a specific receptor.
- Example: "light" is detected by photoreceptors, even if the stimulus is pressure on the eye.
- In the cortex, perception is localized by modality, resulting in specific cortical areas for each sensation.

**Evidence:**
- Within each sensory area, sensations are "mapped" in ways that maintain an orderly representation of the stimulus (e.g., the homunculus in somatosensory cortex; tonotopic maps in auditory cortex; topographic maps in visual cortex).

#### Population Coding (Pattern Theory)

> Sensory information is encoded by the **number and pattern** of participating neural fibers.

**Premises:**
- Some sensory systems (especially taste and olfaction) integrate information across multiple primary afferents.
- A few types of afferent endings are multimodal.
- An ascending pathway can convey sensory information by altering the temporal pattern of action potentials across multiple primary afferents.

**Conclusions:**
- It is the **pattern of activation** of neural networks that forms the basis of perception.

**Evidence:** Examples in the olfactory system and color perception.

**Comparison summary:**

| Feature | Labeled Line | Population Coding |
|---------|-------------|-------------------|
| Representation | One neuron → one stimulus | Pattern across many neurons |
| Upper bound | Limited by number of lines | Many more representations than neurons |
| Robustness to noise | Low | High (redundancy in firing patterns) |
| Example systems | Photoreceptors, taste receptors, somatosensory cortex | Olfactory system |

**Population vector**: The averaged activity of all recorded neurons; the length of each individual line reflects how much each neuron fires; the orientation reflects the preferred direction of each neuron. In bottom-left examples, the actual stimulus direction aligns with the population average even when no single neuron fires maximally in that direction.

---

## Lecture 5: Working Memory II — Canonical Neural Models

*(Date: 2021-11-04)*

### WM Maintenance and the Brain: Delay Period Activity and DLPFC

**Different versions of the delay task** (varying the response requirement): delayed response, delayed recognition, oculomotor delayed response (ODR), delayed match-to-sample, delayed nonmatch-to-sample, etc.

**Core claim:** Neural activity in **DLPFC** during the delay period is thought to be the biological basis of WM. Combined with evidence that DLPFC lesion patients have WM deficits, one theory holds that DLPFC **stores** information during WM.

---

### Issues with Lesions and WM

Lesion effects are **not limited to the delay period**. A DLPFC lesion patient may have impairments in:
- Understanding the task.
- Perceiving the stimuli.
- Executing a response.

**How to isolate maintenance deficits?**

| Method | Assessment | Reason |
|--------|-----------|--------|
| **Remove the delay period** | ❌ Incorrect | Does not rule out encoding, rule maintenance, or response execution confounds |
| **Increase number of items** | ❌ Incorrect | Changes encoding demand (more items to hold in memory); cannot separate maintenance from attention-to-encoding |
| **Increase delay length** | ✅ Correct | Controls everything except the duration of maintenance; greater delay = greater maintenance demand |

**Experimental solution for animal studies — reversible cooling**:
- Brain tissue is cooled (e.g., DLPFC or parietal cortex) to impair function.
- The lesion is **reversible**: the animal recovers when temperature is restored, allowing within-subject comparisons.
- Results: Under normal and parietal-cooling conditions, performance drops at longer delays but stays above 80%. Under **DLPFC cooling**, performance drops nearly to chance — providing strong evidence that DLPFC is specifically required for WM maintenance over delays.

---

### Alternative Theories of DLPFC and WM

What WM-related processes occur during the delay?

1. **Storage of WM item information** — the standard account.
2. **Storage of task rules** (response mapping):
   - Solution: teach participants the rules many days earlier so they are in LTM.
   - Counterargument: even LTM-encoded rules must be *retrieved and actively maintained* during the task — making it almost impossible to dissociate storage of item information from storage of task rules.
3. **Resisting distraction / Attention**:
   - Classic monkey experiment: monkeys with PFC lesions were impaired on delay tasks *except when the lights were turned off*.
   - With no visual input to distract them, performance recovered — suggesting impairment was not in remembering the item itself, but in **maintaining the memory in the face of competing inputs**.
4. **Rehearsal** (though some argue this is not meaningfully distinct from storage).

**Are there other regions with delay-period activity?**

---

### Delay Activity in IT Modules (FFA/PPA)

**Procedure**: Cue → encoding (face or scene) → 12-second delay (fMRI) → match response → long inter-trial interval.

**Findings:**
- During the delay period, **FFA** continues to be active during *face* WM but not scene WM; **PPA** is active during scene WM but not face WM.
- This is a within-subject design; the differences are consistent across subjects despite large error bars.

**Why might the FFA/PPA model be preferable to the pure DLPFC model?**
- If DLPFC alone stores all WM information, there is **competition** between different information types (e.g., faces vs. scenes). The FFA/PPA model involves **compartmentalization of function**.
- **Occam's Razor**: If the brain already has specialized "machinery" (FFA, PPA) for perceiving certain stimuli, it seems redundant and inefficient to also centralize all storage in DLPFC. The brain generally takes the most efficient processing pathway.

**Problems with the IT module model:**
- With virtual lesions of these regions, people can still represent items in WM — suggesting storage is not strictly localized there.
- Does not rule out the **attention confound** (though one counterargument is that WM *is* attention extended over time).
- These regions are dedicated to many functions; resource allocation between maintenance and perception is unclear.
- **Most fundamentally**: delay-period activity is **correlational evidence**, not evidence for storage itself. It shows brain areas are active but does not prove they are necessary for storage.

---

## Lecture 6: Discussion of Funahashi et al.

*(Dates: 2021-11-11 & 2021-11-16)*

### Paper 9: Mnemonic Coding of Visual Space in the Monkey's Dorsolateral Prefrontal Cortex

*(Funahashi, Bruce, & Goldman-Rakic)*

#### Overall Design and Aim

- **Aim**: Demonstrate that DLPFC neuron activity *is* the storage mechanism during WM — a strong claim that storage occurs in DLPFC via **labeled line coding**.
- **Why emphasize direction?** Direction brings specificity to each neuron, supporting construction of a memory map. There is ecological validity in both "where" (location) and "how" (mechanism) regarding each neuron.
- **General critique**: The delivery is not always straightforward; content does not consistently relate back to the main purpose.

#### Method: Oculomotor Delayed-Response (ODR) Task

- Fixation point appears → peripheral cue stimulus presented in one of 8 (or 4) directions → delay period (3–6 seconds) → fixation disappears → monkey makes saccade to remembered location → reward → inter-trial interval (ITI).
- **Why some firing during ITI?** Could result from eye movement, or the neuron may be inhibited by fixation. Not critical — what matters is the elevated activity during the delay period.

#### Results

##### Task Performance

- Distribution of saccade endpoints is wider in the delay task than in the visually guided saccade task, but nearly all saccades land near the appropriate location even with 6-second delays.
- **Critique**: Graphs show distributions of eye positions only, not accuracy (could be 100% or 0% correct).
- **Critique (recurring: "losing data")**: Data are converted from quantitative coordinates to qualitative categories throughout the paper.

##### Neural Data Summary

Of 288 principal sulcus (PS) neurons recorded:

| Classification | Count | Percentage |
|---------------|-------|------------|
| Had task-related activity | 170 | 59% |
| Had no task-related activity | 118 | 41% |
| Had significant delay period activity (of task-related) | 87 | 51% (~30% of total) |
| Delay period activity only | 33 | 38% of delay-active |
| Had significant activity in segments before/after delay | 54 | 62% of delay-active |

- **Critique**: Three monkeys used but differences between monkeys not specified. Generalizability is questionable, especially as the sample narrows to ~20 neurons.

##### Directional Specificity of Delay Activity

Of the 87 PS neurons with delay-period activity:
- **69 (79%)** were **directional** — statistically significant differences in delay-period discharge across different cue locations.
- **18 (21%)** were **omnidirectional** — responded similarly regardless of cue location.

Excitatory/inhibitory breakdown:

| Response Type | Directional | Omnidirectional | Total |
|---------------|------------|-----------------|-------|
| Excitation | 46 | 4 | 50 |
| Inhibition | 23 | 14 | 37 |
| **Total** | **69** | **18** | **87** |

**Polar plot legend:**
- Radius of circle = baseline (ITI) rate.
- Radial bar length = standard deviations of delay-period discharge per direction.
- Asterisks = statistically significant departures from ITI rate.

**Neuron types:**
- **A & B**: Very sharply tuned (1 direction); significant inhibition at roughly opposite directions.
- **C & D**: Directional but broadly tuned. C: excitatory only; D: inhibitory only.
- **E & F**: Omnidirectional. E: excitatory; F: inhibitory.

**Probable functions of omnidirectional neurons:**
1. Contribute to population coding.
2. Help with fixation or preparation for response.

##### Distribution of Preferred Directions

- Majority of excitatory directional neurons had preferred directions on the **contralateral side** to the recorded hemisphere.
- Inhibitory directional neurons showed no statistically significant directional preference, though most were also contralateral.
- **Critique (recurring: "losing data")**: Mixing 4-direction and 8-direction studies makes the results less convincing.

##### Time Course of Delay Activity

- PS neuron activity is well-maintained during a 3-second delay.
- Overall delay activity shows a phasic increase during the response period for both excitatory and inhibitory neurons.

##### Effects of Different Delay Durations

- Varying delay length had little effect on delay activity.
- Directional preference was unchanged; excitation/inhibition simply expanded with longer delays.
- The activity during the first 1.5 seconds is similar across delay conditions; the second 1.5 seconds shows a gradual increase in the 3s and 6s conditions.

##### Delay Activity in Error Trials

- PS neuron responses during the delay were **significantly weaker** when the monkey made an error.
- On error trials, neuron discharge either ceased about midway through the delay or was totally absent.
- **Critique (recurring: "losing data")**: Binarizing results (correct vs. incorrect) loses information; it would be more informative to examine whether the amount of delay activity scales continuously with response accuracy.

##### FEF Neurons

- FEF neurons also showed tonic excitation during the delay period.
- FEF delay activity exhibited presaccadic excitation at the time of response when the monkey made a saccade to the neuron's preferred direction.
- FEF delay activity was suppressed when the cue was at the roughly opposite direction to the preferred direction — similar to PS neurons.

##### Cortical Distribution

- Researchers were unable to identify clear localization or clustering of directional vs. omnidirectional neurons within the PFC.
- **Critique**: Possibly because too many neurons were recorded without sufficient focus; the lack of clustering is a real limitation.

---

#### Major Critiques of Funahashi et al.

##### Population Coding (Not Addressed)

The paper does not account for population coding. Labeled-line analysis of individual neurons is insufficient to explain the monkeys' behavior:
- You cannot use a single neuron to recreate the monkey's behavior.
- Sharply tuned neurons: if neuron B fires slightly less, does this mean the monkey is equally accurate or less accurate?
- Broadly tuned neurons are even harder to interpret individually.
- **Population analysis is crucial** for deriving valid conclusions.

##### Challenging the Evidence for Storage

The paper assumes delay activity equals storage, but there are two very different ways the monkey could solve the ODR task:

- **Retrospective coding**: "What did I see?" — memorizing the sensory position of the cue.
- **Prospective coding**: "What do I need to do?" — planning a saccade to that position (motor intention).

**Is this distinction necessary?** Both constitute WM in some sense. However, the distinction matters critically if the paradigm changes (e.g., to a match task). The experimenters partially addressed this by adding a visually guided saccade, making prospective saccade planning during the delay useless. But:
- **Attention confound**: What if the monkey is not remembering the location or planning a saccade, but simply *sustaining attention* to the part of space where the cue appeared?
- The boundary between attention and WM becomes fuzzy.
- Dissociating these processes would require additional experimental manipulations (e.g., inserting an attention-demanding task during the delay).

---

## Lecture 7: Working Memory III — Contemporary Neural Models

*(Date: 2021-11-16)*

### IT Modules Continued: Is IT a "Dumb" Repetition Detector?

**Experimental design**: Monkeys maintain a picture in WM. Alongside standard trials, **ABBA trials** are included — a stimulus (B) appears in the middle of the delay, serving as an intervening item.

**Logic**: If a neuron "likes" the sample, its firing rate during the delay should be elevated.

**Findings:**
- **IT neurons** responded to stimulus **repetition** (the second B in an ABBA trial) regardless of WM relevance — a behaviorally *irrelevant* repeat.
- **PFC neurons** showed stimulus-specific delay-period activity even across intervening stimuli — a behaviorally *relevant* repeat.

> **Conclusion**: PFC maintains WM information; IT responds to repeats regardless of WM task relevance.

**Potential critique**: Passive maintenance of stimulus repetition might itself be a form of WM, and PFC may be performing "maintenance plus judgment" since PFC also governs control and decision-making.

---

### Multivoxel Pattern Analysis (MVPA)

**MVPA** leverages the pattern of BOLD fMRI activity across voxels — rather than averaging activity in a region.

- An algorithm (called a **classifier**) is trained on some trials and tested on new trials.
- Successful classification of new trials means the pattern of activity contains **meaningful information**.
- Key measure: **classifier accuracy** — whether it is above chance.

**Applying MVPA to WM:**
- Task: encode either color or orientation and store in WM.
- Logic: if MVPA can decode the maintained feature from delay activity, there is strong evidence for storage of specific WM features.
- Result: the classifier correctly decoded **only the relevant feature** (orientation or color) from delay activity in visual cortex — not the irrelevant feature.

> **Conclusion**: WM features are stored in patterns of activity in the **visual cortex**.

- This was also shown to hold despite the presence of a **distracting item** during the delay.
- Though early visual cortex (not IT) is implicated, this finding acts as a rebuttal to the idea of a "dumb IT": visual regions can actively maintain specific WM representations.

---

### Reconciling PFC and Visual Cortex Findings

The monkey experiment shows PFC maintaining information; the human fMRI experiment shows visual cortex maintaining information. How can these be reconciled?

| Difference | Monkey Study | Human Study |
|-----------|-------------|-------------|
| **Technique** | Single-unit recording (individual neurons) | fMRI/MVPA (BOLD signal; large neural populations) |
| **Training** | 3–4 months, restricted 8-direction stimulus set | Verbal instructions |
| **Organism** | Monkey | Human |

**Key implication**: Monkeys are likely **highly overtrained** with a restricted stimulus set, potentially encoding information differently than in natural conditions. They may code information via motor plans (clock positions) rather than sensory representations. Humans and monkeys may not be performing the same cognitive operations despite performing the same behavioral task.

---

### An Alternative to Delay-Period Firing: Activity-Silent WM

**Standard view**: WM is maintained by persistent firing of tuned neurons during the delay.

**Alternative — Activity-silent WM**: When the stimulus disappears, neurons no longer fire persistently, but instead **temporarily change their connection strengths** (synaptic weights).

| | Persistent Firing | Activity-Silent |
|--|---|--|
| **Metabolic demand** | High | Low |
| **Mechanism** | Sustained depolarization | Synaptic weight changes |
| **Explanation for simultaneous perception + WM** | Difficult | Possible |
| **Experimental detection** | Straightforward | Very difficult |
| **Mechanism clarity** | Clear | Unclear |

**If activity-silent WM is real, why do we observe persistent firing?**
- Firing patterns in raster plots are **not consistent across trials** — averages hide high variance.
- Persistent firing may be an **epiphenomenon** of the strengthened connections — a byproduct rather than the cause of storage.

---

### Are All Things in WM Equal?

**Retro-cue experiment**: During the delay, a cue indicates which item you are most likely to be tested on. Participants show better performance on **validly retro-cued items** relative to invalidly cued or neutral trials.

> **Conclusion**: We can **retroactively boost or dampen memory strength** for items already held in WM. (This is non-trivial — informing in advance is trivial because one can simply encode the cued item more strongly.)

**Evidence for different states in WM:**
- Ongoing area of debate: Are there qualitatively different stages? Is "strength" simply a quantitative difference, or are the stages qualitatively distinct?
- **Speculation**: WM may involve different brain regions with different mechanisms, and these may map onto qualitatively different memory states.

---

## Lecture 8: Summary & Comparison of 3 Recent Papers

*(Presented by Treedom, 2021-11-21)*

### Comparative Table of the Three Papers

| | **Worden et al.** (Paper 7) | **Navalpakkam & Itti** (Paper 8) | **Funahashi et al.** (Paper 9) |
|---|---|---|---|
| **Title** | Anticipatory Biasing of Visuospatial Attention Indexed by Retinotopically Specific α-Band EEG Increases over Occipital Cortex | Top-Down Attention Selection is Fine-Grained | Mnemonic Coding of Visual Space in the Monkey's Dorsolateral Prefrontal Cortex |
| **Test subjects** | Human | Human | Monkey |
| **Method** | EEG | Eye tracking | Single-unit recording |
| **Brain area recorded** | Occipital cortex | N/A (eye movements) | Prefrontal cortex within and surrounding principal sulcus (DLPFC) |
| **Task** | One stimulus designated as target; fixation; cue direction to attend; button press if target detected | Luminance example: 3 intervals (low/mid/high); target in one interval (known in advance); 25 Ls + one upside-down L; find target; eye fixations recorded | Fixation point → cue at one of 8/4 locations while eye fixated → delay → fixation disappears → saccade to remembered location → reward → ITI |
| **Main conclusion** | Sustained focal increases of alpha-band activity over occipital cortex contralateral to the ignored location (ipsilateral to cued attention direction) | Top-down attention selection is fine-grained | Monkeys show directionally specific delay-period activity; the brain stores information by maintaining tuned neuron firing for the preferred direction during the delay |

---

### Main Critiques

#### Worden et al. (EEG / Alpha-Band)

- **No neutral trials** designed to establish a baseline.
- **No neural test of mechanism**: no direct test of the neural mechanism underlying the alpha effect.
- **EEG spatial resolution**: Although the researchers selected electrodes based on expected differences in activity (not by identifying sources first), the general limitation of EEG is that the source of activity cannot be determined.
- **No differentiation between motion and direction**: There should be differences in alpha-band activity between motion processing and direction processing given the spatial topographic organization of visual cortex (dorsal vs. ventral); the study does not distinguish these.
- **No condition showing absence of attention**: Did not show what would happen without any attentional deployment.
- **Blink exclusions**: Many blinks were removed from analysis in what appears to be a somewhat subjective process, reducing reproducibility.
- **Rejected trials**: Percentages of excluded trials reported without clarifying whether these overlap across conditions.

#### Navalpakkam & Itti (Eye Tracking / Fine-Grained Attention)

- **Shape confound**: The sensory input between the target and other stimuli is not identical except in the tested dimension — the upside-down L differs in *shape* from the upright Ls. Participants could simply search for the shape and ignore the luminance dimension. Fix: include upside-down Ls in non-target feature intervals.
- **Too few fixations**: There are very few fixations before the target is found (3 out of 25), and even within the target interval (3 out of 8), suggesting a **parallel search** rather than serial guidance.
- **What counts as "fine-grained"?**: Three luminance intervals may not constitute genuine fine-grained processing — this threshold deserves clearer definition.
- **Did not show absence of attention condition**: Did not show what would happen with no top-down guidance.
- **Speed-accuracy trade-off**: Not addressed.
- **Small sample (3 subjects)**: Limited generalizability despite the low-level nature of the task.

#### Funahashi et al. (Single-Unit Recording / DLPFC)

- **Population coding not addressed**: Analysis is based on individual labeled-line coding rather than population coding. Some neurons are broadly tuned to multiple directions, making labeled-line interpretation sub-optimal.
- **Retrospective vs. prospective coding**: It is hard to determine whether the monkeys are maintaining a retrospective sensory representation of the cue position or a prospective intention to make a saccade. Could be addressed by: (a) inserting a visually guided saccade before the final saccade (making prospective planning useless), or (b) using a match response (button press) instead of an eye movement response.
- **WM vs. attention confound**: Cannot be sure whether neurons reflect memory storage or sustained spatial attention. Could be addressed by inserting an attention-demanding task during the delay.
- **Monkey source not specified**: 200 neurons not attributed to specific monkeys; when narrowed to ~20 neurons, generalizability becomes questionable if all come from one monkey.
- **Binary analysis**: Correct vs. incorrect responses discards continuous data; a continuous measure of angular error would be more informative.
- **Possible weighting**: Although behavioral output is discrete, the brain may perform probabilistic weighting across neurons — not captured by the binary analysis.
- **Over-training**: Neurons tuned to specific directions only emerged after extensive training on a very limited stimulus set. The way monkeys now encode information may differ fundamentally from how they would do so in nature.

---

### Why These Studies Are Important

| Paper | Significance |
|-------|-------------|
| **Worden et al.** | Reveals changes in alpha-band (inhibitory) processing during the anticipatory deployment of attention to spatial locations. Attention is critical for survival, and understanding how we drive it is fundamental. We previously did not know whether alpha-band changes during WM delays reflect actual storage or other processes. |
| **Navalpakkam & Itti** | Demonstrates that attention is important for survival and characterizes how precisely top-down signals can guide visual search. |
| **Funahashi et al.** | One of the first papers to directly address that delay-period activity in DLPFC has something to do with *storage* — not just task management or attention. Directional selectivity during the delay period provides evidence that the firing represents stored information. Spatial WM is also important to evolutionary function. |

---

*End of Module 3: Attention & Working Memory*
