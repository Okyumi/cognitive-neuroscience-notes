# Attention II-III: Neural Models, Control of Attention; Eye Tracking (2021-10-14 & 2021-10-26)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## Neural Models of Attention

### Biased Competition Model (Desimone & Duncan, 1995)

- Multiple stimuli compete for neural representation and behavioral control.
- **Attention biases** the competition in favor of the attended stimulus.
- Competition occurs at multiple levels of the visual hierarchy.
- Attended stimulus → enhanced neural representation; unattended stimuli → suppressed.

![Biased competition model: two stimuli competing for representation in IT cortex; attention to one suppresses response to the other](images/pdf2-110.png)

### Neurophysiology: Single-Unit Recordings (Moran & Desimone, 1985)

- Monkey V4/IT neurons: when two stimuli are in the receptive field, response is an **average** of the two stimuli responses.
- When attention is directed to one stimulus, the response **shifts toward** the attended stimulus response.
- Attention effectively **shrinks** the receptive field around the attended stimulus.

### Normalization Model of Attention (Reynolds & Heeger, 2009)

- Attention modulates the **gain** of neural responses via divisive normalization.
- Predicts different effects of attention depending on **stimulus size** vs. **attention spotlight size**:
  - Stimulus smaller than attention spotlight: **response gain** (multiplicative scaling).
  - Stimulus larger than attention spotlight: **contrast gain** (shifts contrast-response function).

---

## Control of Attention: Top-Down vs. Bottom-Up

### Salience Map

- A spatial map of the visual scene weighted by **saliency** (conspicuity).
- Bottom-up saliency: contrast with surround (color, orientation, motion, size).
- Top-down modulation: task goals bias the salience map.

![Itti & Koch (2001) salience map model: feature maps (color, intensity, orientation) combined into a master salience map for guiding attention](images/pdf2-112.png)

### Winner-Take-All and IOR

- The most salient location wins the competition → attention shifts there.
- After attending, **inhibition of return (IOR)**: the previously attended location is suppressed to allow exploration of new locations.

---

## Frontal Eye Fields (FEF) and Attentional Control

- **FEF** (precentral gyrus): classically a motor area for saccades, but also modulates visual processing.
- TMS to FEF **enhances** visual processing at the corresponding retinotopic location.
- FEF sends top-down signals to visual cortex to modulate attention.

---

## Parietal Cortex and Spatial Attention

- **IPS (intraparietal sulcus)**: encodes a **priority map** of visual space.
- Damage → **hemispatial neglect**: failure to attend to the contralesional side.
- **LIP (lateral intraparietal area)**: in monkeys, codes the **expected value** of making a saccade to a location (combines saliency and task relevance).

---

## Attentional Blink

- **Attentional blink (AB)**: in Rapid Serial Visual Presentation (RSVP), if two targets appear close in time (200–500 ms), the second target (T2) is often missed.
- Reflects a **bottleneck** in the consolidation of target 1 into working memory.
- T2 is processed sensory-wise, but not consolidated — **"labile"** representation.

![Attentional blink paradigm and typical AB curve showing T2 accuracy as a function of lag between T1 and T2](images/pdf2-113.png)

---

## Eye Tracking

### How Does Eye Tracking Work?

- **Video-based eye tracking**: infrared light illuminates the eye; camera records corneal reflections and pupil position.
- **Dual Purkinje image tracking**: uses multiple reflections from cornea and lens for high precision.

### Key Eye Movement Types

- **Fixations**: gaze held relatively still (20–200 ms); visual information primarily acquired here.
- **Saccades**: rapid, ballistic eye movements (20–200 ms); **suppression of visual processing during saccades** (saccadic suppression).
- **Smooth pursuit**: eye tracks a moving object; requires prediction.
- **Microsaccades**: tiny saccades during attempted fixation; may serve to refresh the retinal image.

---

## Saccadic Eye Movements

### Metrics

- **Amplitude**: in degrees of visual angle.
- **Latency**: time from target onset to saccade onset (~150–250 ms).
- **Accuracy**: primary saccade lands close to target; corrective saccades follow.

### Neural Control of Saccades

- **Superior colliculus (SC)**: key structure for triggering saccades; receives input from FEF, LIP.
- **FEF**: cortical control of voluntary saccades.
- **Cerebellum**: fine-tuning saccade accuracy.

---

## Eye Tracking as a Measure of Attention

- Where people look reflects what they are attending to.
- **Gaze-contingent paradigms**: display changes based on where the participant is looking.
- **Scanpaths**: sequence of fixations and saccades reflect visual processing strategy.

### Applications

- Reading research: fixation duration → lexical processing difficulty.
- Scene viewing: fixations cluster on informative regions.
- Marketing/UX: heatmaps of webpage viewing.
- Clinical: saccade abnormalities in schizophrenia, Parkinson's, ADHD.

---

## The Saliency Map and Eye Movements

- Itti & Koch (2001): saliency model predicts where people look in natural scenes.
- But: **task demands** override bottom-up saliency.
  - Yarbus (1967): different task instructions → completely different scanpaths on the same image.

![Yarbus (1967) scanpath study: different instructions (estimate ages, remember positions of people, etc.) produce distinct scanpath patterns on the same scene](images/pdf2-115.png)

---

## Corollary Discharge and Saccadic Suppression

- When a saccade is planned, a **corollary discharge** (efference copy) is sent to visual areas to suppress the blur that would occur due to the eye movement.
- Without this mechanism, the world would appear to move every time we move our eyes.
