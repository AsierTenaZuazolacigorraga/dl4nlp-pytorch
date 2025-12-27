# Deep Learning for NLP - PyTorch Implementation

This repository contains PyTorch implementations of laboratory assignments from the **Natural Language Processing for Deep Learning** course at UPV/EHU (University of the Basque Country), provided by [HiTZ Zentroa](https://www.hitz.eus/).

## About

These labs were originally developed using Keras/TensorFlow. This repository presents a complete rework of all assignments using **PyTorch**, maintaining the same concepts and learning objectives while leveraging PyTorch's API and design patterns.

## Labs

The course consists of 5 hands-on laboratories covering fundamental deep learning architectures for NLP:

1. **Logistic Regression** - Introduction to neural networks with a simple classification model
2. **Multi-Layer Perceptron (MLP)** - Building deeper feed-forward networks
3. **LSTMs** - Sequential modeling with Long Short-Term Memory networks
4. **Attention for NLI** - Attention mechanisms for Natural Language Inference tasks
5. **Transformers** - Modern transformer architectures for NLP

## Repository Structure

Each lab is available in two versions:
- **Keras version** (`*_with_Keras_sol.ipynb`) - Original implementations
- **PyTorch version** (`*_with_Pytorch.ipynb`) - Reworked implementations

## Viewing Notebooks

**Note:** Most notebooks in this repository are not displayed correctly on GitHub (only Lab 1 Keras and Lab 2 PyTorch render properly). For the best viewing experience, please use one of the following options:

- **[nbviewer](https://nbviewer.org/)** - Paste the notebook URL for proper rendering
- **Clone the repository** and open locally with Jupyter:
  ```bash
  git clone https://github.com/YOUR_USERNAME/dl4nlp-pytorch.git
  cd dl4nlp-pytorch
  jupyter notebook
  ```

### Direct nbviewer links:

**PyTorch Implementations:**
- [Lab 1: Logistic Regression](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/1_Logistic_Regression_with_Pytorch.ipynb)
- [Lab 2: MLP](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/2_MLP_with_Pytorch.ipynb)
- [Lab 3: LSTMs](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/3_LSTMs_with_Pytorch.ipynb)
- [Lab 4: Attention for NLI](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/4_Attention_for_NLI_with_Pytorch.ipynb)
- [Lab 5: Transformers](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/5_Transformers_with_Pytorch.ipynb)

**Original Keras Implementations:**
- [Lab 1: Logistic Regression](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/1_Logistic_Regression_with_Keras_sol.ipynb)
- [Lab 2: MLP](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/2_MLP_with_Keras_sol_.ipynb)
- [Lab 3: LSTMs](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/3_LSTMs_with_Keras_sol.ipynb)
- [Lab 4: Attention for NLI](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/4_Attention_for_NLI_with_Keras_sol.ipynb)
- [Lab 5: Transformers](https://nbviewer.org/github/YOUR_USERNAME/dl4nlp-pytorch/blob/main/5_Transformers_with_Keras_sol.ipynb)

*Note: Replace `YOUR_USERNAME` with your actual GitHub username in the links above.*

## Requirements

For running the PyTorch implementations:
```bash
pip install torch numpy jupyter matplotlib
```

## Acknowledgments

Course materials provided by HiTZ Zentroa, UPV/EHU.
