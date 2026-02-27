# TMS Demonstration; Discussion of Wang et al. (2021-12-07)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## TMS Demonstration (2021-12-07)

### Transcranial Magnetic Stimulation (TMS)

- TMS is a method for temporarily and reversibly modulating electrical activity in the brain.
- It operates under the principle of the right-hand rule, which relates electricity and magnetism.
- The logic is similar to that of lesion studies: observe how TMS changes behavior; infer the causal function of the region.
- TMS can modulate a brain area with the size around a small coin, but the signal cannot go deeply.
  - Therefore, there are challenges to study the LTM because structures in MTL are too deep to perform TMS.

![TMS setup diagram: wire coil placed over participant's head; pulsed magnetic field induces electrical currents in stimulated brain region (maximum field depth shown); activated neurons vs. resting neurons illustrated. Adjacent: photograph of a figure-eight TMS coil.](images/pdf2-472.png)

---

### Important Things to Consider

**Where to apply the TMS pulse?**
- Everyone's brain is different!
- Neuronavigational software!

![Six-panel neuronavigation image (a–f): (a–c) 3D brain reconstruction in gold/green, showing TMS target localization in MRI space; (d–f) coronal and sagittal MRI slices with target coordinate marked. Adjacent: photograph of researcher applying TMS to participant in a neuronavigation setup.](images/pdf2-473.png)

**What intensity should you use?**
- Everyone's brain is different!
- Most common way: base it on **motor threshold**! (Active vs. resting motor threshold)
- **Phosphine threshold** (stimulate primary visual cortex, see flashes), etc.

![Diagram of motor evoked potential (MEP) measurement: TMS coil above head → pyramidal neuron (layer V) → corticospinal axon → pyramidal decussation → synapse in spinal gray matter → surface EMG on hand muscle. Right panel shows example EMG waveforms: MEP, SICI (short-interval intracortical inhibition), ICF (intracortical facilitation), TCI, CSP (cortical silent period) at 0.5 mV scale / 100 ms timescale.](images/pdf2-474.png)

![Additional diagram illustrating the relationship between TMS intensity, motor threshold determination, and the electrophysiological signals recorded from hand muscles](images/pdf2-475.png)

---

**What stimulation protocol should you use?**
- How many pulses and in what pattern?
- Different patterns have different effects.
  - HF & LF: High frequency → excitatory. Low frequency → inhibitory. (Mimic lesion)
  - R vs. SP: Repetitive → longer-lasting effects. Single pulse → effect goes away quickly.

![Stimulation protocol diagram showing pulse patterns over 1 second: LF rTMS (low frequency — sparse pulses), HF rTMS (high frequency — dense pulses), cTBS (continuous theta burst stimulation — dense continuous burst pattern), iTBS (intermittent theta burst stimulation — bursts separated by gaps, with 3-pulse train and 8s interval labeled)](images/pdf2-476.png)

- Online vs. offline.
  - **Online**: Stimulate the participants during the experiment.
  - **Offline**: Stimulate the participants before the experiment. (Need long-lasting effects → repetitive TMS)
    - Long-lasting effects: best done with **cTBS** (continuous theta burst stimulation protocol).
    - c vs. i: Intermittent has increased excitability whereas continuous has decreased excitability.

**What is an appropriate control?**
- Within or between subjects?
  - If you can, always do a within-subject design.
- No TMS? Sham TMS? Vertex TMS?
  - No TMS. [Con: the whole process is different in terms of leading up to the experiment.]
  - Sham TMS: Orient the coil perpendicularly. The pulse goes out. [Con: subjects may feel the difference.]
  - Vertex TMS: TMS the task-irrelevant brain area. (e.g., vertex, somatosensory cortex)

**Safety:**
- TMS is generally safe, but should be used carefully.
- Not in individuals with a history of seizures or migraines.
- Participants should have eaten beforehand.
- Participants should be warned about the potential for discomfort or odd sensations.

---

### Resting State fMRI

- Identify networks of the brain. (Correlations of BOLD signals overtime)
- TMS is a method for temporarily and reversibly modulating electrical activity in the brain.

![Resting-state fMRI diagram: three brain regions highlighted (red = M1/TPJ area, green = IFG area, blue = another node) on lateral brain view. Three BOLD signal time-course plots displayed: TPJ timecourse (red), M1 timecourse (middle), IFG timecourse (green) — each spanning ~6 minutes. Correlation values annotated: r=0.12, r=0.67, r=0.19. Label: "Spontaneous brain activity in a subject at rest." Illustrates how resting-state connectivity is measured by correlating spontaneous BOLD fluctuations across regions.](images/pdf2-477.png)

---

## Discussion of Wang et al. (2021-12-09)

### Paper 10: Targeted Enhancement of Cortical-Hippocampal Brain Networks and Associative Memory (Targeted Enhancement of Cortical-Hippocampal Brain Networks and Associative Memory)

**Aim**: investigate the cortical hippocampal interaction with the lateral parietal cortex (LPC).

**Method**:

![Panel A: Coronal MRI slice showing hippocampal target (seed), and 3D brain rendering with stimulation location (TMS target on lateral surface) highlighted, plus MRI-guided stimulation delivery illustration. Panel B: Study design timeline — Week 1 and Week 2, Day 1–7. Day 1 = Baseline (assessment only). Days 2–6 = alternating stimulation session (dark green) / sham session (orange) / assessment (gray). Day 7 = Post-Tx (assessment). Shows counterbalanced crossover design.](images/pdf2-478.png)

- Stimulation vs. sham control vs. negative control (motor cortex)
- Critique: room for improvement: it is better if the experimenters stimulate an area in LPC with no functional connectivity with the hippocampus.

**Design**:
- Half stimulation first, half sham first → Get rid of the confounding of time.
- Critique: participants can feel sensational differences between stimulation and sham. What if the differences were caused by the sensation?
- Argument back: at time 1, before the participants tell whether they got TMSed or not (they were naïve), the stimulation and control groups were already different.

**Measure**:
- The accuracy of associative task (LTM-declarative-episodic).
- The experimenters did not directly TMS the hippocampus (too deep to TMS).
- They took an anatomical target in hippocampus [seed] and stimulate a functionally closely related region — LPC [target].
- The seed and the target are in the same network.

**Search for the seed**:
- The experimenters have to choose the seed first, and then they individuate the LPC in subjects.
- To find out where in the hippocampus that they want to indirectly stimulate, they selected a coordinate which robustly shows functional connectivity with LPC in a group level study.
- There might be differences in the brain across individuals, so the experimenters worked everyone's brain in a common template as a reference and then take the coordinate to work backwards in the individual's brain. Brain → Coordinate → Brain
- The experimenters finally searched for a voxel in each participant that was the closest to the coordinate.

**Search for the target**:
- Data-driven: resting state fMRI, looking for some voxels for which the correlation of activity to the seed is high.
- Hypothesis-driven: previous literature has stated the high connectivity between LPC and the hippocampus.

---

### Results

**How much these regions were talking to each other after 5 day's TMS:**

![Panel A: Brain rendering showing all regions with increased functional connectivity after stimulation relative to sham (warm color = increase in connectivity). Bar graph showing mean ΔfMRI connectivity across brain regions — stimulation (green) significantly higher than sham (orange) and motor-cortex stimulation (blue). Illustrates global networkness increase.](images/pdf2-479.png)

![Panel B: Hippocampal target shown on brain; line graph of ΔfMRI connectivity vs. distance from hippocampal target (−9 to +9mm) — sharp peak at 0mm for stimulation condition (green), flat for sham (orange). Demonstrates high spatial specificity: connectivity increase is greatest at the targeted region and drops off rapidly with distance.](images/pdf2-480.png)

- **A**: all the regions were more functionally connected after the stimulation relative to sham. (Increase the networkness)
- Critique: the experimenters did not mention whether there was a clear change between the seed and the target.
- **B**: After stimulating a region connected to the seed, the change in the global brain networkness was specially increased in the target.
- High specificity: if you move a bit away from the seed, there is much less global connectivity.
- TMS was only affecting the regions that have a high baseline connectivity with the seed.

![Connectivity–memory correlation figures: Panel A (left) — matrix heatmap of baseline functional connectivity across brain regions; Panel B (middle) — scatter plot showing correlation between ΔfMRI connectivity and number of correct pairs recalled (R²=0.282, p<0.0001), positive relationship; Panel C (right) — heatmap showing in-network vs. out-network connectivity changes, with warm colors inside the network and cool outside, demonstrating network-specific enhancement.](images/pdf2-486.png)

![Memory performance results: Panel A — Study task: 20 face/word pairs shown (faces paired with objects: chair, hat, car); Association memory test: face shown, choose correct word. Panel B — line graph of memory performance change (Y-axis −0.2 to 0.5) across Baseline, Mid-Tx, Post-Tx. Stimulation (green line) increases over sessions; Sham (orange) remains flat. Statistical markers: * p<0.05, ** p<0.01.](images/pdf2-487.png)

![Panel A (right): Bar graph showing ΔMemory Performance — Stimulation (green, ~0.4) significantly higher than Sham (orange, ~0.1) and Motor-cortex stimulation (blue, ~0.0). Panel B: Bar graph showing ΔfMRI connectivity — only Stimulation group shows significant positive change; Sham and Motor-cortex are near zero or negative.](images/pdf2-488.png)

![Panels C and D: Panel C — brain rendering showing TMS target location (LPC) with seed-target connectivity highlighted. Panel D — scatter plot of ΔMemory performance vs. ΔfMRI connectivity; positive correlation across individuals (blue dots, blue line). Demonstrates that individuals with greater connectivity increase also showed greater memory improvement.](images/pdf2-489.png)

- There is an improvement in memory performance in stimulation relative to sham.
- Critique: the therapeutic effect was not long-lasting.
- Critique: did not differentiate between WM and LTM.
- Critique: a face that test all the time; forgetting might be a major confound.
- Result: (not improvement) less of the worsening. (Test the associative memory in general)
