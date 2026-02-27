# Eye-Tracking Demonstration; Discussion of Navalpakkam & Itti (2021-10-28)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## Eye-Tracking Demonstration

![Social media post (WeChat, "洞悉寰宇的小傻子" / "The Little Fool Who Sees Through the Universe") showing a person in traditional Chinese costume holding a large bow, with colorful geometric patterns overlaid](images/pdf2-126.png)

![Eye-tracking heatmap of a scene image: fixation density visualized as a colored heat map with red/yellow clusters indicating high fixation density and blue regions indicating fewer fixations](images/pdf2-127.png)

---

## Paper 10: Modeling the Influence of Task on Attention

*(Navalpakkam & Itti, 2005)*

---

## Summary

- Navalpakkam & Itti proposed a model for how **task (top-down) goals** influence **attentional selection** in visual search.
- Extended the **Itti & Koch (2001)** saliency model by adding a **task-dependent top-down weight map**.
- Key insight: the brain doesn't just compute bottom-up saliency — it **reweights** feature maps based on the current task goal (e.g., searching for a red target).

---

## Key Concepts

### Task-Dependent Reweighting

- When searching for a target with feature F, the weight of the feature map for F is **increased**.
- This biases the salience map toward locations containing feature F.
- **Top-down attention = reweighting of feature maps**.

### Optimal Reweighting

- Navalpakkam & Itti went further: the optimal weight for a feature is proportional to the **discriminability** of the target from distractors on that feature.
- High discriminability (target very different from distractors) → high weight.
- Low discriminability → low weight.
- This is equivalent to a **signal detection theory** framework: weight each feature by its **d'** (sensitivity) for discriminating target from distractors.

---

## Critical Evaluation

### Strength 1: Computational precision

- The model makes **quantitative, testable predictions** about which features should guide attention.
- Can be compared directly to human performance data.

### Strength 2: Accounts for task effects

- Explains why people are better at finding targets when the target feature is highly discriminable from distractors (feature conjunction effects).

### Strength 3: Bridges bottom-up and top-down attention

- Provides a principled framework for combining bottom-up saliency with top-down task goals.

### Limitation 1: Behavioral validation only

- Model validated on RT/accuracy data — no direct neural evidence provided.

### Limitation 2: Feature space is limited

- Model uses a predefined set of features (color, orientation, intensity, motion).
- Real visual search involves far more complex features.

### Limitation 3: Static model

- Does not account for **temporal dynamics** of attention (how attention unfolds over time in a search display).

---

## Broader Implications

- Supports the view that attention is **task-dependent**, not purely stimulus-driven.
- Consistent with **biased competition** model: top-down goals bias the competition in favor of task-relevant features.
- Relates to **feature-based attention**: attending to a feature enhances its representation globally across the visual field.
- Has applications in **computer vision** (saliency-based image processing) and **human factors** (designing interfaces to capture user attention).
