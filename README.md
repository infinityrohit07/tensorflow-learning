# TensorFlow Learning

A hands-on learning repository for understanding Machine Learning and Deep Learning with Python, TensorFlow, and Keras.

The goal of this repository is to build concepts gradually through explanations, examples, visualizations, and practical exercises.

## Learning roadmap

| # | Topic | What you'll learn |
|---|---|---|
| 01 | Introduction to Machine Learning | AI vs. ML vs. DL, learning types, features, labels, models, and predictions |
| 02 | TensorFlow and tensors | Tensor creation, shapes, data types, indexing, and tensor operations |
| 03 | Neural network fundamentals | Neurons, weights, biases, activation functions, and layers |
| 04 | Your first neural network | Build a simple model with `tf.keras` |
| 05 | Training and evaluation | Loss functions, optimizers, epochs, batches, and evaluation |
| 06 | Regression | Predict continuous values using neural networks |
| 07 | Classification | Predict categories and evaluate classification models |
| 08 | Improving models | Validation, overfitting, underfitting, and regularization |
| 09 | Computer vision | Introduction to image datasets and neural networks |
| 10 | Projects | Apply the concepts to small end-to-end problems |

> The roadmap is a guide. Notebooks will be added as each topic is covered.

## Repository structure

```text
tensorflow-learning/
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   ├── 01-introduction-to-machine-learning.ipynb
│   ├── 02-tensorflow-and-tensors.ipynb
│   ├── 03-neural-network-fundamentals.ipynb
│   └── ...
├── datasets/
│   ├── raw/
│   └── processed/
├── images/
└── src/
```

- `notebooks/`: explanations, code examples, visualizations, and exercises.
- `datasets/raw/`: original datasets. Keep large or private data out of Git.
- `datasets/processed/`: cleaned or transformed datasets, when appropriate.
- `images/`: diagrams and images used in the notes.
- `src/`: reusable Python code as the project grows.

## Getting started

### Option 1: Google Colab

1. Open a notebook in Google Colab.
2. Select **File → Save a copy in GitHub**.
3. Choose this repository and the `main` branch.
4. Save it inside the `notebooks/` folder using the naming convention below.

You can also open notebooks from GitHub in Colab using:

```text
https://colab.research.google.com/github/<YOUR-GITHUB-USERNAME>/tensorflow-learning/blob/main/notebooks/<NOTEBOOK-NAME>.ipynb
```

Replace `<YOUR-GITHUB-USERNAME>` and `<NOTEBOOK-NAME>` with your GitHub username and notebook filename.

### Option 2: Run locally

Create and activate a virtual environment.

**Windows:**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install the dependencies:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

## Notebook naming convention

Use lowercase names, hyphens, and a two-digit sequence number:

```text
01-introduction-to-machine-learning.ipynb
02-tensorflow-and-tensors.ipynb
03-neural-network-fundamentals.ipynb
04-first-neural-network.ipynb
```

Keep one main topic per notebook. Add a new number when introducing a new notebook, and avoid spaces or names such as `final-notes-new.ipynb`.

## Notebook style

For consistency, each learning notebook should follow this general order:

1. **Learning objectives** — what the notebook covers.
2. **Concepts** — clear explanations and definitions.
3. **Examples** — small, commented code examples.
4. **Visualizations** — charts or diagrams where useful.
5. **Practice** — exercises to check understanding.
6. **Summary** — key takeaways.

Use Markdown cells for explanations and code cells for executable Python. Keep outputs useful, and restart and run all cells before committing the notebook.

## Dependencies

See [`requirements.txt`](requirements.txt) for the Python packages used when running the notebooks locally.

Google Colab already includes many common data-science packages. You usually do not need to install everything again in Colab.

## Progress

- [ ] Introduction to Machine Learning
- [ ] TensorFlow and tensors
- [ ] Neural network fundamentals
- [ ] First neural network
- [ ] Training and evaluation
- [ ] Regression
- [ ] Classification
- [ ] Improving models
- [ ] Computer vision
- [ ] Practical projects

## Notes

- This is a learning repository; examples and notebooks will evolve as concepts are explored.
- Do not commit API keys, passwords, private datasets, virtual environments, or large generated files.
