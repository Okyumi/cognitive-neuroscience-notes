# High-Level Vision III: Distributed Representations; MVPA (2021-09-23)

> Course: PSYCH-UH 2412 Cognitive Neuroscience | NYU Abu Dhabi | Authors: Sean Shan Guangji & Yumi Omori

---

## The Distributed Representation View

- Not just FFA for faces, PPA for places, etc.
- Category information is **distributed** across large swaths of ventral temporal cortex.
- Haxby et al. (2001): even after removing the maximally responding region, category information can still be decoded.

![Haxby et al. (2001) diagram showing distributed patterns for different object categories across ventral temporal cortex](images/pdf2-037.png)

---

## Multi-Voxel Pattern Analysis (MVPA)

- Also called **decoding** or **pattern classification**.
- Uses **machine learning** classifiers to decode stimulus category from spatial patterns of BOLD activity.

### Key Idea

- Instead of asking "is this voxel more active for faces than houses?", ask "does the **pattern** of activity across voxels carry information about the stimulus category?"

### Procedure

1. Collect fMRI data while subjects view different categories.
2. Extract pattern of BOLD activity for each trial.
3. Train a classifier (e.g., SVM, linear discriminant) to predict category from pattern.
4. Test on held-out data (cross-validation).
5. Accuracy above chance → category information present in that region.

---

## Representational Similarity Analysis (RSA)

- Compare the **geometry** of representations across different levels (e.g., visual cortex, IT, behavior, model).
- Build a **Representational Dissimilarity Matrix (RDM)**: pairwise dissimilarities between all stimulus pairs in a given space.
- Compare RDMs across levels using correlation.

![Representational Dissimilarity Matrix (RDM) for different brain regions and computational models](images/pdf2-040.png)

---

## Neural Coding Schemes

### Sparse Coding

- Each object activates a small number of neurons very strongly.
- Efficient representation; grandmother cells as extreme case.

### Distributed Coding

- Each object activates many neurons weakly.
- More robust to noise; more capacity.

### Population Coding

- Object identity encoded in the **pattern** of activity across a population of neurons.
- Middle ground between sparse and distributed.

---

## IT Cortex and Object Recognition

- **Inferotemporal (IT) cortex**: the endpoint of the ventral visual stream.
- Neurons in IT respond to complex object features; large, bilateral receptive fields.
- Activity in IT predicts perceptual categorization behavior.

---

## Deep Neural Networks (DNNs) as Models of Visual Cortex

- **AlexNet**, **VGG**, **ResNet**: hierarchical CNNs trained on ImageNet.
- Lower layers → V1/V2 (simple features: edges, gratings).
- Higher layers → V4/IT (complex objects, faces).
- Yamins et al. (2014): DNN layer activations predict IT neuron responses.

---

## Limitations of MVPA

- Decoding accuracy depends on the classifier, preprocessing, and number of voxels.
- Does not tell you **what** information is coded, only **that** information is present.
- Spatial smoothing can reduce pattern information.
