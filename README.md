# PyTorch Testing with Google Colab

This repository serves as a sandbox for testing **PyTorch** functionality within the **Google Colab** ecosystem. It is designed to verify environment configurations, CUDA acceleration, and basic tensor computations without the overhead of local driver installations.

---

## 🚀 Quick Start

The core logic is located in `test1.ipynb`. You can launch the notebook directly in your browser using the badge below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME/blob/main/test1.ipynb)

> **Pro Tip:** To use the GPU, go to `Runtime` -> `Change runtime type` -> `T4 GPU` once the notebook is open.

---

## 📂 Repository Structure

* **`test1.ipynb`**: The primary testing script. It includes:
    * PyTorch version verification.
    * CUDA/GPU availability checks.
    * Basic tensor operations and gradient calculations.



---

## 🛠️ Performance Testing

This project tests the efficiency of PyTorch operations. For example, the notebook may compare CPU vs. GPU performance for matrix multiplications:

$$C = A \times B$$

Where $A$ and $B$ are large matrices, demonstrating the parallel processing power of the Colab-assigned GPU.

---

## 📋 Requirements

No local installation is required. The environment is managed by Google Colab, which provides:
* **Python 3.10+**
* **PyTorch (latest stable)**
* **CUDA Support**

---

## 🤝 How to Contribute

1. Fork this repository.
2. Create a new branch for your tests.
3. Submit a Pull Request with a description of the PyTorch features you are validating.

---

*Created for rapid prototyping and environment validation.*
