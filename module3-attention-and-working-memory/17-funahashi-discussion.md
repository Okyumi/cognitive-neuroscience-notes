# Discussion of Funahashi et al. (2021-11-11 & 2021-11-16)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

[← Back to Main Contents](../README.md) | [← Previous Lecture](16-working-memory-II.md) | [Next Lecture →](18-working-memory-III.md)

---

## Pre-Class Preparation

### A: Background

**Behavioral paradigm: Oculomotor Delayed Response (ODR) task**

- The monkey is required to fixate the fixation point.
- The cue stimulus (a visual stimulus) was presented for 0.5 s at one of eight locations (at 45° intervals, at 13° eccentricity).
- After a 3-second memory delay (intertrial interval), the fixation point was turned off. This was the signal for the animal to make a saccade to the location of the remembered cue.
- Correct trials were rewarded.

**The ODR task can assess WM:**

- It tests if the monkey can remember where the cue is during the 3-second delay period.
- Response is executed at the end of the delay period.
- The cue information must be actively maintained for the task to be completed correctly.

**Area recorded from: DLPFC (principal sulcus / area 46)**

(The principal sulcus is located in the DLPFC.)

---

### B: Single-Unit Recording

**What is a single-unit recording?**

- In a multi-unit recording, we pick up activity from multiple neurons in the vicinity of the electrode tip.
- In a single-unit recording, we want to record from single neurons.
  - The recording electrode is positioned precisely so that the signal we pick up comes from only one neuron.
  - We confirm this by: (1) checking amplitude consistency; (2) refractory period (a neuron cannot fire again within 1 ms).
    - e.g. the signal 0101 means there is no refractory violation: between each spike, there is at least 1 ms.
    - e.g. the signal 011 means there is a refractory violation.
    - This is key because if we see a very high firing rate that violates the refractory period, it means we are picking up activity from more than one neuron.

**Waveform:** how we distinguish between neurons.
- **Action potential**: all-or-nothing electrical impulses.
- Each neuron has a unique shape of action potential waveform.
  - Soma size: related to amplitude.
  - Dendritic arbor: related to the shape.
  - Myelination: related to speed.

---

### C: Raster Plots and Peristimulus Time Histograms (PSTHs)

**Raster plots:**

- A visual display of neural spiking activity, where rows are trials and columns are time.
- Each row: a single trial.
- Each tick: an action potential.
- Time 0: when the stimulus appeared (stimulus onset).

**Peristimulus time histograms (PSTHs):**

- Take average across time within each bin (and also across trials).
- Converts the raster plots into a simple histogram.
- Usually plotted below the raster plot.
- On the x-axis, time; on the y-axis, firing rate (spikes/s or spikes per bin).

---

### D: Receptive Field Mapping & Direction-Selectivity

**Recall:** visual neurons have receptive fields (RFs).
- The neuron fires when a stimulus is in its RF.
- The RF is the part of space that the neuron "responds to" or "prefers".

**Direction-selectivity:**
- Some neurons selectively respond to stimuli presented in a particular direction.
- A direction-selective neuron in DLPFC is a neuron that fires when the cue is presented in a particular location.
  - This is analogous to what is seen in visual cortex (selective responses to visual features).
  - But in DLPFC, it is not just about the sensory input. Rather, the neuron carries information about the location that the monkey needs to remember.

---

### E: The Concept of a "Memory Field"

**Memory field:**
- The preferred location of a neuron during the delay period of the ODR task.
- Analogous to a RF, but for a memory signal, not a sensory signal.
- A neuron with a memory field at 270° fires more during the delay period when the cue was at 270°.

**Directional tuning:**
- A single neuron may fire preferentially for a few neighboring directions.
  - Narrow tuning: selective for a small range of directions.
  - Broad tuning: selective for a wider range of directions.
  - Population code: the pattern of activity across multiple neurons (each broadly tuned) can encode a specific direction precisely.

---

### F: Cue vs. Memory Period Activity

**Cue period activity (sensory):**
- Activity that corresponds to the cue stimulus presentation, not a memory signal.
- Usually strongest right when the cue appears.

**Memory period activity:**
- Activity that persists after the cue has disappeared.
- This is the key finding of the paper: sustained delay activity in DLPFC.

**We need to distinguish the two:**
- A neuron could be responding to the cue itself (sensory response).
- Or it could be maintaining the memory of the cue location (memory signal).
- The delay period lets us separate these:
  - The cue stimulus is gone during the delay period, so activity during the delay is not driven by a sensory stimulus.
  - This is the key argument for why delay period activity is considered a WM signal.

---

### G: What an "Excitatory" vs. "Inhibitory" Memory Field Looks Like in the Data

**Excitatory memory field:**
- The neuron's firing rate increases above baseline during the delay period for the preferred direction.
- Fires more when the cue was in a particular location.

**Inhibitory memory field:**
- The neuron's firing rate decreases below baseline during the delay period for the preferred direction.
- Fires less when the cue was in a particular location.
- This is also a form of memory storage; different neurons may use inhibition vs. excitation to encode location.

---

## Discussion

**Key finding of the paper:**

- A population of DLPFC neurons showed sustained delay-period activity during the ODR task.
- This activity was spatially tuned: each neuron had a preferred direction (memory field).
- This provides evidence that the DLPFC stores spatial WM.

**Why is this important?**

- Established a neural correlate of WM in the PFC.
- Provides evidence for the idea that WM is maintained by sustained neural firing.
- Memory fields are analogous to sensory RFs, suggesting that WM has organized representations in the brain, just as perception does.

---

## In-Class Discussion Questions & Answers

---

**Q: The cue stimulus is a small bright spot, and the animal has to make a saccade at the end of the delay period. How can we be sure that delay-period activity is not due to motor preparation (preparation of an eye movement)?**

**A:**

- One way to address this is to dissociate the cue location from the target location.
  - If delay-period activity is related to memory, it should follow the cue location.
  - If delay-period activity is related to motor preparation, it should follow the target location.
- In ODR, the saccade target is the same as the cue location (the animal has to saccade to where the cue was).
  - But if we change the paradigm so the animal has to saccade to the opposite direction of the cue, we can test whether delay-period activity is memory-related or motor-related.

---

**Q: What is the difference between a directionally tuned cue-period response vs. a directionally tuned memory-period response?**

**A:**

- Both are spatially selective, but the signals are different.
- Cue-period activity: driven by the sensory stimulus. Occurs when the cue is present.
- Memory-period activity: persists after the cue is gone. Must be internally maintained by the brain.
- The key difference: **memory-period activity is not driven by external input**.
  - It is a read-out of information stored in the brain, not a direct response to external stimulus.

---

**Q: Even if a neuron shows sustained activity during the delay period, can we definitively say this neuron is storing WM? What are alternative interpretations?**

**A:**

- Not definitively, because there are alternative interpretations:
  1. **Motor preparation**: the activity reflects preparation of the upcoming saccade.
  2. **Sensory trace**: the activity reflects a lingering sensory response to the cue.
  3. **Attention**: the animal might be directing attention to the cue location.
  4. **Timing**: the activity might reflect the animal's timing of when to respond.
- To be more certain, we would need additional experiments to dissociate these.

---

**Q: The paper compares different types of neurons: those with excitatory memory fields vs. inhibitory memory fields. What are the implications?**

**A:**

- Excitatory and inhibitory memory fields suggest that neurons can use both increases and decreases in firing rate to encode information.
- This adds complexity to our understanding of how information is stored in WM.
- Inhibitory memory fields could reflect a local circuit mechanism where inhibitory interneurons are recruited to suppress activity in non-preferred directions.
- This is consistent with the idea that WM is maintained by a balance of excitation and inhibition in local cortical circuits.

---

**Q: What would be the effect of a lesion to the DLPFC principal sulcus on performance in the ODR task?**

**A:**

- This was actually done by Funahashi et al. in a follow-up paper.
- Lesions to the principal sulcus produced a contralateral mnemonic scotoma:
  - Deficits in remembering cues presented in the contralateral visual field.
  - Performance for ipsilateral cues was relatively spared.
- This provides causal evidence that DLPFC is necessary for spatial WM, not just correlated with it.

---

**Q: In the ODR paradigm, is the monkey remembering the location of the cue, or just preparing a saccade? How do you tell these apart?**

**A:**

- This is a fundamental confound of the ODR task.
- Ways to distinguish:
  - Anti-saccade task: cue appears at one location, but the animal has to saccade to the opposite location.
    - If delay activity follows cue location, it is memory-related.
    - If delay activity follows saccade target, it is motor-related.
  - Some neurons in DLPFC do follow the cue location even when the required saccade is elsewhere, suggesting a true memory signal.

---

**Q: A neuron has a memory field at 90°. What would the raster plot and PSTH look like for the 90° condition vs. the 270° condition?**

**A:**

- For the 90° condition (preferred direction):
  - The raster plot shows dense ticks during the delay period.
  - The PSTH shows elevated firing rate during the delay period.
- For the 270° condition (non-preferred direction):
  - The raster plot shows sparse ticks during the delay period.
  - The PSTH shows firing rate close to or below baseline during the delay period.

---

**Q: The paper says that some DLPFC neurons have excitatory memory fields for one direction and inhibitory memory fields for the opposite direction. What does this suggest about how information is encoded?**

**A:**

- It suggests that neurons use a push-pull (reciprocal) coding strategy.
  - For the preferred direction: the neuron fires above baseline (excitation).
  - For the anti-preferred direction: the neuron fires below baseline (inhibition).
- This is similar to the opponent coding seen in sensory systems (e.g., color opponency in the visual system).
- This coding strategy increases the information that a single neuron can carry and can improve the signal-to-noise ratio in the population.

---

**Q: In what ways is the memory field analogous to a sensory receptive field? In what ways is it different?**

**A:**

- **Analogies:**
  - Both are spatially organized (tuned to particular locations).
  - Both show directional selectivity.
  - Both reflect properties of organized cortical representations.
- **Differences:**
  - A sensory RF is driven by external sensory input; a memory field is driven by an internal, maintained representation.
  - A sensory RF is tied to the presence of a stimulus; a memory field persists even after the stimulus is gone.
  - Memory fields are in the PFC, which is a higher-order association area; sensory RFs are in sensory cortex.

---

**Q: The task requires the monkey to fixate. Why is fixation important in this paradigm?**

**A:**

- If the monkey's eyes move, the retinal location of the cue would shift.
- This could confound the memory signal with a sensory signal (the monkey's gaze-shifted view of the world).
- Fixation ensures that the spatial memory tested is truly allocentric (or at least anchored to a stable reference frame), not just a retinal trace.
- Also, fixation prevents early motor preparation for the saccade during the delay period.

---

**Q: What types of neurons are recorded in this study? How do they differ from neurons in visual cortex?**

**A:**

- DLPFC neurons (specifically, in the principal sulcus, area 46).
- Differences from visual cortex neurons:
  - Visual cortex neurons respond to sensory features (orientation, color, motion, etc.).
  - DLPFC neurons respond to higher-order properties, like the remembered location of a stimulus.
  - Visual cortex neurons are activated mainly when a stimulus is present; DLPFC neurons show sustained firing even after the stimulus is gone.
  - DLPFC neurons are more task-dependent: they may not fire at all if the animal is not doing the WM task.

---

[← Back to Main Contents](../README.md) | [← Previous Lecture](16-working-memory-II.md) | [Next Lecture →](18-working-memory-III.md)