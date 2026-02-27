# Long-Term Memory I: Cellular and Neural Basis (2021-11-18)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

[← Back to Main Contents](../README.md) | [← Previous Lecture](19-working-memory-IV.md) | [Next Lecture →](21-long-term-memory-II.md)

---

## Long-Term Memory (LTM)

- **The ability to store and retrieve information over long periods of time (hours, days, years).**
  - Contrast with WM: seconds to minutes.
- LTM is not a unitary system; there are multiple types of LTM.

---

## Why Studying LTM?

- **Basic science:**
  - LTM underlies the richness of human experience: personal history, knowledge, skills, language.
  - LTM is deeply linked to identity.
- **Clinical relevance:**
  - Memory disorders are prevalent: Alzheimer's disease (AD), amnesia, PTSD.
  - Understanding the cellular basis of LTM may open avenues for treatment.

---

## Types of LTM

| | **Explicit (Declarative)** | **Implicit (Non-Declarative)** |
|---|---|---|
| **Definition** | Consciously accessible | Not consciously accessible |
| **Subtypes** | Episodic (personal events) | Procedural (skills, habits) |
| | Semantic (facts, knowledge) | Priming |
| | | Conditioning |
| **Brain regions** | Hippocampus, MTL | Cerebellum, BG, Amygdala |
| **Example** | "I remember eating sushi last Tuesday" | Riding a bike |

---

## Hippocampus and LTM

- The hippocampus (and surrounding MTL structures) is critical for forming new explicit LTM.
- Landmark case: **Patient H.M. (Henry Molaison)**
  - Bilateral hippocampal removal for epilepsy treatment (1953).
  - After surgery: profound anterograde amnesia (inability to form new explicit memories).
  - Retrograde amnesia for events close to the surgery.
  - Preserved WM: could hold information for short periods.
  - Preserved implicit memory: could learn new skills (e.g., mirror drawing), but had no conscious recollection of learning them.
  - **Key insight:** The hippocampus is necessary for forming new explicit LTM, but not for WM or implicit memory.

---

## Cellular Basis of LTM: Long-Term Potentiation (LTP)

- **LTP: a long-lasting increase in synaptic strength following high-frequency stimulation.**
- First described by Tim Bliss and Terje Lømo (1973) in the hippocampus.

### The Hebb Rule

> "Neurons that fire together, wire together."

- If neuron A repeatedly fires just before neuron B, the synaptic connection from A to B is strengthened.
- This is the cellular basis of associative learning.

### NMDA Receptors and LTP

- **NMDA receptor**: a type of glutamate receptor that acts as a "coincidence detector".
  - It requires BOTH:
    1. Presynaptic release of glutamate.
    2. Postsynaptic depolarization (i.e., the postsynaptic cell must already be active).
  - When both conditions are met, calcium (Ca²⁺) enters the postsynaptic cell.
  - Ca²⁺ triggers a cascade of molecular events that ultimately lead to:
    - Insertion of more AMPA receptors into the synapse.
    - Increased synaptic strength.

<p align="center">
  <img src="../images/pdf3-012.png" alt="Diagram of NMDA receptor mechanism: presynaptic terminal releasing glutamate; NMDA receptor with Mg²⁺ block (removed when postsynaptic membrane is depolarized); Ca²⁺ influx into postsynaptic neuron; downstream molecular cascade leading to AMPA receptor insertion" width="600">
</p>

*Diagram of NMDA receptor mechanism: presynaptic terminal releasing glutamate; NMDA receptor with Mg²⁺ block (removed when postsynaptic membrane is depolarized); Ca²⁺ influx into postsynaptic neuron; downstream molecular cascade leading to AMPA receptor insertion*

---

### LTP Induction Protocol

- **High-frequency stimulation (HFS):** tetanic stimulation (e.g., 100 Hz for 1 s).
  - This mimics the natural pattern of neural activity that would occur during learning.
- **Result:** Persistent increase in EPSP amplitude after HFS.
  - The synapse is now "potentiated".

<p align="center">
  <img src="../images/pdf3-014.png" alt="LTP induction graph: x-axis = time (minutes), y-axis = EPSP slope (% of baseline); a baseline period, then a tetanic stimulation (arrow), then a sustained elevated EPSP slope (LTP)" width="600">
</p>

*LTP induction graph: x-axis = time (minutes), y-axis = EPSP slope (% of baseline); a baseline period, then a tetanic stimulation (arrow), then a sustained elevated EPSP slope (LTP)*

---

### Properties of LTP

1. **Cooperativity:** LTP is only induced when multiple inputs are co-activated.
   - Weak stimulation of a single pathway is insufficient; co-activation of multiple inputs is required.
2. **Associativity:** A weak input can be potentiated if it is co-active with a strong input.
   - Consistent with the Hebb rule.
3. **Specificity:** LTP is input-specific; only the synapses that were active get potentiated.
   - This allows for selective strengthening of relevant synapses.

---

### Phases of LTP

| Phase | Time | Mechanism |
|---|---|---|
| Early LTP (E-LTP) | Minutes to hours | Phosphorylation of existing proteins (e.g., AMPA receptors) |
| Late LTP (L-LTP) | Hours to days (and beyond) | New protein synthesis; gene expression; structural changes |

- L-LTP requires:
  - Activation of CREB (cAMP response element-binding protein) transcription factor.
  - New mRNA synthesis and protein production.
  - Structural changes at the synapse (e.g., growth of dendritic spines).

---

## Morris Water Maze

- A behavioral test for spatial memory in rodents.
- The rat is placed in a pool of opaque water and must find a hidden submerged platform.
- The rat uses distal visual cues to navigate to the platform.
- **Key finding:** Rats with hippocampal lesions cannot learn the location of the platform (impaired spatial LTM).
  - They swim randomly, unable to use spatial cues.
  - But they can still find a visible platform (visual and motor systems intact).

<p align="center">
  <img src="../images/pdf3-018.png" alt="Morris water maze diagram: circular pool with a hidden platform; example swim paths for control rat (direct path to platform) vs. hippocampal-lesion rat (random path); probe trial bar graph showing % time in target quadrant for control vs. lesion" width="600">
</p>

*Morris water maze diagram: circular pool with a hidden platform; example swim paths for control rat (direct path to platform) vs. hippocampal-lesion rat (random path); probe trial bar graph showing % time in target quadrant for control vs. lesion*

---

## Place Cells and Grid Cells

### Place Cells (hippocampus)

- **Place cell:** a neuron in the hippocampus that fires when the animal is in a specific location (the neuron's "place field").
  - Discovered by John O'Keefe (Nobel Prize 2014).
  - Together, the ensemble of place cells forms a cognitive map of the environment.

<p align="center">
  <img src="../images/pdf3-022.png" alt="Place cell figure: top-down view of a maze or open field with a color map (hot = high firing rate, cold = low firing rate) showing a single neuron's place field concentrated in one region" width="600">
</p>

*Place cell figure: top-down view of a maze or open field with a color map (hot = high firing rate, cold = low firing rate) showing a single neuron's place field concentrated in one region*

### Grid Cells (entorhinal cortex)

- **Grid cell:** a neuron in the entorhinal cortex that fires at multiple locations, forming a regular hexagonal grid pattern across the environment.
  - Discovered by Edvard and May-Britt Moser (Nobel Prize 2014, shared with O'Keefe).
  - Grid cells are thought to provide a coordinate system that place cells use to form a cognitive map.

<p align="center">
  <img src="../images/pdf3-024.png" alt="Grid cell figure: top-down view of an open field with a color map showing a regular hexagonal pattern of high-firing-rate spots spread across the environment" width="600">
</p>

*Grid cell figure: top-down view of an open field with a color map showing a regular hexagonal pattern of high-firing-rate spots spread across the environment*

---

## Episodic Memory and the Hippocampus

- **Episodic memory:** memory for specific personal events ("what happened, where, and when").
- The hippocampus is thought to bind together the different elements of an episode (what, where, when).
  - This is sometimes called the **binding function** of the hippocampus.

### Episodic Memory in Non-Human Animals?

- **Scrub jays (Nicola Clayton's work):**
  - Scrub jays cache food and can remember what they hid, where they hid it, and when (recency).
  - This is taken as evidence for episodic-like memory in non-human animals.
  - They preferentially recover perishable food (worms) before non-perishable food (nuts), if they learned that worms decay faster.

---

## Reconsolidation

- After retrieval, a memory becomes temporarily labile (unstable) and must be re-stored (reconsolidated).
- **Implication:** memories are not static; they can be modified at the time of retrieval.
- **Clinical relevance:** targeting reconsolidation could be used to modify or weaken traumatic memories (PTSD treatment).

---

## Systems Consolidation: Standard Model vs. Multiple Trace Theory

### Standard Model (Squire & Alvarez, 1995)

- Initially, new memories depend on the hippocampus.
- Over time (through sleep and replay), memories are gradually transferred to neocortex.
- Old memories become hippocampus-independent.

### Multiple Trace Theory (Nadel & Moscovitch, 1997)

- Each time a memory is retrieved, a new trace is laid down in the hippocampus.
- Episodic memories remain hippocampus-dependent, regardless of their age.
- Semantic memories (general facts) can become hippocampus-independent over time.

---

## Sleep and Memory Consolidation

- Sleep plays a critical role in consolidating new memories.
- During sleep (especially slow-wave sleep):
  - The hippocampus "replays" recent experiences.
  - This replay is thought to gradually transfer information to the neocortex.
- **Evidence:** Sleep deprivation after learning impairs memory consolidation.

---

## Summary

- LTM is supported by LTP at the cellular level and the hippocampus at the systems level.
- LTP is induced by coincident activity (NMDA receptor as coincidence detector), consistent with Hebb's rule.
- The hippocampus is essential for forming new explicit memories (Patient H.M.) and supports spatial navigation (place cells).
- Memory consolidation involves a gradual shift from hippocampal to neocortical storage, mediated by sleep replay.

---

[← Back to Main Contents](../README.md) | [← Previous Lecture](19-working-memory-IV.md) | [Next Lecture →](21-long-term-memory-II.md)