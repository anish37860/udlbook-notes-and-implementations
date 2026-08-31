# 🧠 Understanding Deep Learning — Notes & Implementations

[![Book Website](https://img.shields.io/badge/Official_Book-udlbook.com-blue.svg)](https://udlbook.github.io/udlbook/)
[![Publisher](https://img.shields.io/badge/Publisher-MIT_Press-red.svg)](https://mitpress.mit.edu/9780262048644/understanding-deep-learning/)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/Framework-PyTorch-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
![Views](https://hitscounter.dev/api/hit?url=https%3A%2F%2Fgithub.com%2Fanish37860%2Fudlbook-notes-and-implementations%2Ftree%2Fmain&label=Views&icon=github&color=%238540f5&message=&style=flat&tz=Asia%2FKolkata)

This repository contains my personal notes, core takeaways, and completed Python/PyTorch implementations for the coding exercises in **[Understanding Deep Learning](https://udlbook.github.io/udlbook/)** by **[Simon J.D. Prince](https://www.linkedin.com/in/simon-prince-615bb9165/)** (MIT Press).

---

## 📖 Book & Author Details

* **Title:** *Understanding Deep Learning*
* **Author:** [Simon J.D. Prince](https://x.com/SimonPrinceAI) (Former Honorary Professor at University College London, Honorary Professor at University of Bath, and AI Researcher)
* **Publisher:** [The MIT Press](https://mitpress.mit.edu/9780262048644/understanding-deep-learning/)
* **Official Resources:**
  * 🌐 **Official Site:** [udlbook.github.io/udlbook](https://udlbook.github.io/udlbook/)
  * 📄 **Free Book PDF:** [Download Book Draft](https://udlbook.github.io/udlbook/)
  * 📦 **Official Exercise Code:** [udlbook GitHub Org](https://github.com/udlbook/udlbook)
  * 📽️ **Lecture Materials:** [Slides & Interactive Figures](https://udlbook.github.io/udlbook/)

---

## 📊 Implementation & Progress Tracker

> **Status Legend:** ✅ Completed | 🏗️ In Progress | ⏳ Pending

| Chapter | Topic / Domain | Status | Completion Date | Core Notebooks & Implementations |
| :--- | :--- | :---: | :---: | :--- |
| **01** | Introduction & Math Foundations | ✅ | Aug 31st, 2026 | Matrix operations, linear algebra review |
| **02** | Supervised Learning Basics | 🏗️ |  | 1D Supervised learning pipeline |
| **03** | Shallow Neural Networks | ⏳ | | Activation functions, region partitioning |
| **04** | Deep Neural Networks | ⏳ | | Network composition, clipping functions |
| **05** | Loss Functions | ⏳ | | Least Squares, Binary & Multiclass Cross-Entropy |
| **06** | Fitting Models & Optimization | ⏳ | | Line search, SGD, Momentum, Adam optimizer |
| **07** | Gradients & Backpropagation | ⏳ | | Manual & automatic backprop, Xavier/He initialization |
| **08** | Performance Evaluation | ⏳ | | Bias-variance tradeoff, double descent phenomenon |
| **09** | Regularization Strategies | ⏳ | | $L_2$ regularization, implicit regularization, data augmentation |
| **10** | Convolutional Networks (CNNs) | ⏳ | | 1D & 2D convolutions, downsampling, upsampling |
| **11** | Residual Networks & Norms | ⏳ | | ResNets, Batch Normalization, shattered gradients |
| **12** | Transformers & Attention | ⏳ | | Self-attention, multi-head attention, decoding strategies |
| **13** | Graph Neural Networks (GNNs) | ⏳ | | Graph embeddings, GAT, neighborhood sampling |
| **14** | Unsupervised Learning | ⏳ | | Latent variables, density estimation, clustering foundations |
| **15** | Generative Adversarial Networks | ⏳ | | Minimax optimization, Wasserstein GANs |
| **16** | Normalizing Flows | ⏳ | | 1D & Autoregressive flows, contraction mappings |
| **17** | Variational Autoencoders (VAEs) | ⏳ | | ELBO optimization, reparameterization trick |
| **18** | Diffusion Models | ⏳ | | Forward/reverse SDEs, score matching, 1D diffusion |
| **19** | Deep Reinforcement Learning | ⏳ | | MDPs, Dynamic Programming, Monte-Carlo, TD methods |
| **20** | Why Deep Learning Works | ⏳ | | Lottery ticket hypothesis, high-dimensional geometry |
| **21** | Responsible AI & Ethics | ⏳ | | Bias mitigation, explainable AI (SHAP / LIME) |

---

## 🗺️ Learning Roadmap & Core Topics Covered

### **Phase 1: Foundations & Optimization**
- **Mathematics:** Matrix calculus, linear algebra, vector transformations.
- **Network Architectures:** Shallow vs. deep neural networks, activation functions, function composition.
- **Fitting & Gradients:** Loss functions (Cross-Entropy, MSE), Line Search, SGD, Momentum, Adam, and manual backpropagation.

### **Phase 2: Generalization & Computer Vision**
- **Model Evaluation:** Bias-Variance trade-off, double descent, high-dimensional space dynamics.
- **Regularization:** $L_2$ penalty, implicit regularization, ensembling, Bayesian neural networks, and data augmentation.
- **CNNs & ResNets:** Convolutions, pooling layers, residual connections, and Batch Normalization.

### **Phase 3: Attention, LLMs & Graphs**
- **Transformers:** Scaled dot-product self-attention, multi-head attention, tokenization, positional encodings, and decoding strategies (Greedy, Top-$k$, Nucleus).
- **Graph Neural Networks:** Graph representation, node classification, neighborhood sampling, and Graph Attention Networks (GAT).

### **Phase 4: Deep Generative Models**
- **GANs:** Minimax optimization, generator/discriminator dynamics, Wasserstein distance.
- **Normalizing Flows:** Normalizing flows, autoregressive flows, change of variables.
- **VAEs:** Latent variable models, Evidence Lower Bound (ELBO), reparameterization trick.
- **Diffusion Models:** Forward and reverse diffusion, score matching, SDE formulations.

### **Phase 5: RL, Theory & Ethics**
- **Reinforcement Learning:** Markov Decision Processes (MDPs), Dynamic Programming, Monte-Carlo methods, and Temporal Difference learning.
- **Deep Learning Theory:** High-dimensional geometry, lottery ticket hypothesis, gradient flow, and adversarial robustness.
- **Responsible AI:** Bias mitigation, explainability algorithms (LIME, SHAP, counterfactuals), differential privacy.

---

## 🛠️ Tech Stack & Key Competencies

* **Core Stack:** Python, PyTorch, NumPy, Matplotlib, SciPy.
* **Engineering Skills Demonstrated:**
  * Writing custom neural network layers and training loops without heavy abstraction frameworks.
  * Vectorized implementations of loss functions, attention mechanisms, and backpropagation.
  * Debugging gradient pathologies (shattered gradients, vanishing/exploding gradients).
  * Implementation of modern generative models (Diffusion, VAEs, GANs, Flows).

---

## 📌 Citation

```bibtex
@book{prince2023understanding,
  author    = {Simon J.D. Prince},
  title     = {Understanding Deep Learning},
  publisher = {The MIT Press},
  url       = {[http://udlbook.com](http://udlbook.com)}
}
