# CS1090B — Section Notebooks (2026)

Section materials for **CS1090B: Introduction to Deep Learning** (Harvard, Spring 2026).
Notebooks are written in **PyTorch** and designed to run in Google Colab or locally.

Instructors: Pavlos Protopapas, Kevin Rader, Chris Gumb

## Repository Layout

Each `sec{NN}/` folder contains:

- `cs1090b_sec{NN}_student.ipynb` — exercises with starter code
- `cs1090b_sec{NN}_solutions.ipynb` — completed reference solutions
- `data/`, `fig/` — datasets and figures used by the notebook
- `notebook_assets.zip` — bundled assets (downloaded automatically by the notebook setup cell)

## Sections

### Section 1 — Anatomy of a Neural Network
Build an MLP from first principles (affine transforms, activations, layers), then re-implement it in PyTorch.
[Student](sec01/cs1090b_sec01_student.ipynb) · [Solutions](sec01/cs1090b_sec01_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec01/cs1090b_sec01_student.ipynb)

### Section 2 — Training Neural Networks
Regression with neural nets, weight initializers, and optimizers (incl. effect of batch size).
[Student](sec02/cs1090b_sec02_student.ipynb) · [Solutions](sec02/cs1090b_sec02_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec02/cs1090b_sec02_student.ipynb)

### Section 3 — Regularization
Early stopping, L1/L2 weight decay, and dropout for regression. *Two variants available — main and alternative.*
[Student](sec03/cs1090b_sec03_student.ipynb) · [Solutions](sec03/cs1090b_sec03_solutions.ipynb) · [Alternative Student](sec03/cs1090b_sec03_student_alternative.ipynb) · [Alternative Solutions](sec03/cs1090b_sec03_solutions_alternative.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec03/cs1090b_sec03_student.ipynb)

### Section 4 — Convolutional Neural Networks
CNN building blocks (conv, pool, flatten, dropout, GAP), LeNet from scratch, and KMNIST classification.
[Student](sec04/cs1090b_sec04_student.ipynb) · [Solutions](sec04/cs1090b_sec04_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec04/cs1090b_sec04_student.ipynb)

### Section 5 — SOTA Architectures & Transfer Learning
Inception, ResNet, and friends from `torchvision`; feature extraction vs. fine-tuning.
[Student](sec05/cs1090b_sec05_student.ipynb) · [Solutions](sec05/cs1090b_sec05_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec05/cs1090b_sec05_student.ipynb)

### Section 6 — Dimensionality Reduction & Clustering
PCA, scree plots, explained variance, and k-means; choosing the number of components.
[Student](sec06/cs1090b_sec06_student.ipynb) · [Solutions](sec06/cs1090b_sec06_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec06/cs1090b_sec06_student.ipynb)

### Section 7 — Autoencoders & Variational Autoencoders
Convolutional autoencoders, latent-space visualization, and CVAEs for conditional generation.
[Student](sec07/cs1090b_sec07_student.ipynb) · [Solutions](sec07/cs1090b_sec07_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec07/cs1090b_sec07_student.ipynb)

### Section 8 — Text Preprocessing & Embeddings
Tokenization, padding, numerical encoding, and feed-forward baselines on IMDB.
[Student](sec08/cs1090b_sec08_student.ipynb) · [Solutions](sec08/cs1090b_sec08_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec08/cs1090b_sec08_student.ipynb)

### Section 9 — Recurrent Neural Networks
Vanishing/exploding gradients, GRU, LSTM, bidirectional and deep stacked RNNs on IMDB.
[Student](sec09/cs1090b_sec09_student.ipynb) · [Solutions](sec09/cs1090b_sec09_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec09/cs1090b_sec09_student.ipynb)

### Section 10 — Hugging Face & BERT Fine-Tuning
`AutoModel`/`AutoTokenizer`, batch encoding, and fine-tuning BERT for sentence classification.
[Student](sec10/cs1090b_sec10_student.ipynb) · [Solutions](sec10/cs1090b_sec10_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec10/cs1090b_sec10_student.ipynb)

### Section 11 — Instruction Tuning (SFT)
Supervised fine-tuning from scratch: chat templates, PyTorch dataset/dataloader, manual training loop, perplexity evaluation.
[Student](sec11/cs1090b_sec11_student.ipynb) · [Solutions](sec11/cs1090b_sec11_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec11/cs1090b_sec11_student.ipynb)

### Section 12 — Vision Transformers, CLIP & Diffusion
ViTs and attention-map visualization, zero-shot classification with CLIP, semantic image retrieval, and text-to-image diffusion.
[Student](sec12/cs1090b_sec12_student.ipynb) · [Solutions](sec12/cs1090b_sec12_solutions.ipynb) · [![Open Student in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Harvard-CS1090/2026_CS1090B_public/blob/main/sec12/cs1090b_sec12_student.ipynb)

## Running the Notebooks

**Colab (recommended):** click the *Open in Colab* badge above for any section. The setup cell downloads any required data automatically.

**Locally:** clone this repo and open the notebook. You'll need a Python environment with `torch`, `torchvision`, `transformers`, `numpy`, `pandas`, `matplotlib`, and `scikit-learn` (specific versions vary by section).

## Reproducibility

All notebooks set seeds at the top of the setup cell:
```python
np.random.seed(109)
torch.manual_seed(109)
torch.cuda.manual_seed_all(109)
torch.backends.cudnn.deterministic = True
```

## License & Attribution

Released under the [MIT License](LICENSE.txt). If you adapt or redistribute these materials, please credit the course:

> Protopapas, P., Rader, K., & Gumb, C. (2026). *CS1090B: Data Science II*. Harvard University. https://github.com/Harvard-CS1090/2026_CS1090B_public

Some materials build on prior versions of the course and on third-party sources cited within individual notebooks; those retain their original licenses.
