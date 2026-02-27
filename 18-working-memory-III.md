# Working Memory III: Contemporary Neural Models (2021-11-16)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## IT Modules Continued; Is IT a "Dumb" Repetition Detector?

- The experimenters had monkeys maintain one of these pictures. When the monkey saw something that they had to remember, they would let go of a lever that they held.
- Besides the standard trials, there are also ABBA trials with stimulus repeating in the middle, serving as intervening.
- Graph interpretation: if a neuron likes the sample, the firing rate during the delay should be elevated. A neuron likes the sample – solid line; a neuron hates the sample – dash line.
- The experimenter contrasted the stimulus repetition and WM.

![Left: Schematic of standard and ABBA trial structures. Standard trials: sample → multiple nonmatching test items → matching test. ABBA trials: sample → nonmatch → nonmatch → repeated nonmatch (a.k.a. 2nd B in ABBA) → nonmatch → match. 0.5 sec stimulus presentation, 1 sec delays. Right: Line graph of spikes per second over time from sample onset (0–8000 ms), comparing activity following best sample (solid line) vs. worst sample (dashed line). Shaded regions indicate sample, nonmatch, nonmatch, nonmatch, nonmatch, match periods.](images/pdf2-232.ppm)

- **Neurons in IT responded to stimulus repetition (i.e., 2nd B in ABBA trials) and not just WM.**
  - Behaviorally irrelevant repeat.
- **Only PFC neurons showed stimulus-specific delay period activity across intervening stimuli.**
  - Behaviorally relevant repeat.
- Conclusion: PFC maintains WM info, while IT responds to repeats regardless of WM.
- Potential critique: the passive maintenance of repetition might be WM itself, and PFC is performing the maintenance plus judgment because PFC also takes charge of control and decision making.

---

## Below: A Rebuttal to "Dumb" IT

### Multivoxel Pattern Analysis (MVPA)

(The pattern of purple looks more like a scene.)

- Leverages the pattern of BOLD fMRI activity across voxels.
  - Make predictions by averaging the amount of activity of neurons in a brain area.
- An algorithm (called classifier) is used to train on some trials, and then test on a new set of trials.
- Successful ability to classify new trials means that the pattern of activity contains meaningful information.
- The key measure is "classifier accuracy": whether or not it is above chance.

![Diagram illustrating MVPA: a brain with visual cortex highlighted, showing avg BOLD activity columns (green, blue, purple) each with 3×3 voxel patterns. The three patterns correspond to a face stimulus, a scene stimulus, and an unknown/test stimulus ("???"). MVPA uses the spatial pattern of BOLD activity to classify which item is being maintained.](images/pdf2-233.ppm)

---

## Applying MVPA to WM

- **Task:** encode either color or orientation and store in WM.
  Feature: orientation & color.

![Stimuli used in the MVPA WM task: grating stimuli shown at Sample (1 s), Delay (10 s), and Test (1 s) phases, with ITI (10 s). Stimuli have both orientation and color features, but participants are told to remember only one.](images/pdf2-234.ppm)

- **Logic:** if MVPA can decode the specific maintained orientation/color from delay activity, then there is strong evidence for the storage of specific WM features.
- **Result:** classifier could correctly guess only the relevant feature from the pattern of delay activity in visual cortex. WM features are stored in patterns of activity in the visual cortex.
  - Even though the stimulus could have an orientation and a color, the classifier could not tell the irrelevant feature.
- Subsequently shown that memory decoding in the visual cortex is successful despite the presence of a distracting item.

![Left: Bar graph (a) of WM Delay classification accuracy for Orientation and Color stimulus features, with separate bars for "Remember Orientation" (red) and "Remember Color" (teal). Chance level indicated at ~0.5. Classifier accurately decodes only the relevant feature. Right: Timeline diagram showing sample (0.5s) → delay 1 (9.5s) → distractor (0.5s) → delay 2 (9.5s) → method-of-adjustment response (4.0s), with grating stimuli at each point.](images/pdf2-235.ppm)

- **Though this is the early visual cortex rather than IT, the study could serve as a rebuttal to the idea of dumb IT.**
  - Visual regions can store information in WM: the visual cortex still holds on to the orientation they saw before despite the disruption from randomly other orientations.
- (When no information is on the screen, the signal-to-noise ratio is lower and thus increases the classification difficulty).

---

## Below: Potential Reconciliation

### Could We Reconcile?

- The monkey experiment shows that PFC is maintaining information, but the human experiment shows that the visual cortex is maintaining information. How can we potentially reconcile these two seemingly incompatible results?
  - **Different techniques:** single-unit recording (firing of individual neurons) vs. fMRI (BOLD signal which is indirectly related to neuron firing and is a recording of large numbers of neurons).
  - **Different organisms:** monkeys do the tasks differently than humans.
    - How to train humans? Verbal orders.
    - How to train monkeys? For 3–4 months for 8 directions only. The monkeys are not doing the tasks in the same ways as we would in nature.
      - They may be highly overtrained with a restricted stimulus set.
      - If we train to do the task every day, we can code in other methods, for example, clock positions.

---

## Below: Alternative to Delay Study

### An Alternative to Delay Study?

- **Delay activity:** a persistent firing of tuned neurons.
- **Alternative:** when we take away the faces, the neurons no longer fire, but they change their connection strength.
- **Activity silent:** temporary changes in connection strengths between tuned neurons.

![Diagram illustrating activity-silent WM: two sets of neurons (left: connected network with strong synapses; right: a simpler two-neuron representation). In activity-silent storage, the information is maintained through temporarily strengthened synaptic weights rather than persistent firing.](images/pdf2-236.ppm)

- **Pros:**
  - Less metabolically demanding.
  - Potential explanation for simultaneous perception and WM.
- **Cons:**
  - Unclear mechanism for changing connections.
  - Hard to demonstrate experimentally!
- If this is true, why do we see persistent firing?
  - One issue with the raster plots is that the firing patterns are not consistent across trials. In experiments, we take averages, but the values are with high standard deviations.
  - One potential explanation is that firing is an epiphenomenon of the strengthened connections. (A result that the system stores like this.)

---

## Below: Are All Things in WM Equal?

### Are All Things in WM Equal?

- **Retro-cue experiment:** during the delay, there is a retro-cue that tells you the item that you will likely be tested on.
- **Better performance on validly retro-cued items relative to invalidly retro-cued items or neutral trials.**
  - → Retroactively change the strength (either boosting or dampening the memory) of items within the memory.

![Diagram of the retro-cue experiment: (a) retro-cue condition — sample display (two colored squares) → blank → retro-cue (arrow indicating one item) → blank → probe display (color wheel with test square); (b) neutral-cue condition — sample display → blank → uninformative stimulus (asterisk) → blank → probe display.](images/pdf2-237.ppm)

- The experiment is significant as it shows that we can do something to the memory after it is done. (It is trivial to inform ahead of time as people can pay more attention to the one and dedicate more resources in WM during encoding.)
- **Evidence for different states in WM?**
  - Area of debate: whether or not there are different stages; how is information (differently) maintained; is the strength of the memory different or the stages are qualitatively different?
  - Speculation: WM involves different brain regions and has different mechanisms, and maybe these different regions and mechanisms map on different states.
