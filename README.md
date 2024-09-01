# ML-NLP-Projects

This repository contains implementations of various Machine Learning and Natural Language Processing projects.

## Projects

### 1. MIFS-NN (Mutual Information Feature Selection with Neural Network)

Location: `ML-NLP-Projects/MIFS-NN/`

This project demonstrates the Mutual Information Feature Selection (MIFS) algorithm using a neural network. It uses the Wisconsin Breast Cancer dataset for demonstration.

Key features:

- Implementation of MIFS algorithm
- Neural Network demonstration
- Hyperparameter optimization

For more details, see the [MIFS-NN README](MIFS-NN/README.md).

### 2. NLP-PyTorch-Skipgram

Location: `ML-NLP-Projects/NLP-PyTorch-Skipgram/`

This project implements the Skip-Gram model for word embeddings using PyTorch. It includes two separate implementations:

a) Using Reuters Corpus:

- File: `MikolovEtAl_Reuters.ipynb`
- Contributors: Raphael Steinborn, Lidia Makishti, Vineeth Racharla, Saqib Sarwar

b) Using Custom Corpus:

- File: `MikolovEtAl_CustomCorpus.ipynb`
- Main Contributor: Raphael Steinborn

Key features:

- Skip-Gram model implementation
- Word similarity calculations
- Visualization of word embeddings (Custom Corpus version)
- Evaluation of vector compositionality (Custom Corpus version)

For more details, see the [NLP-PyTorch-Skipgram README](NLP-PyTorch-Skipgram/README.md).

## Requirements

- Python 3.x
- PyTorch
- NumPy
- Pandas
- Matplotlib
- NLTK
- SciPy
- Scikit-learn (for CustomCorpus version of Skip-Gram)

## Usage

Each project folder contains Jupyter notebooks that can be run to see the implementations in action. Please refer to the individual project READMEs for specific instructions.

## Limitations

- MIFS-NN: The project uses a specific dataset and may require adjustments for other datasets.
- NLP-PyTorch-Skipgram (Reuters): Limited computational resources restricted hyperparameter tuning and implementation of additional features.
- NLP-PyTorch-Skipgram (CustomCorpus): The small custom corpus, while faster to train, lacks the size for advanced analogical tasks.

## References

- Battiti, R. (1994). Using mutual information for selecting features in supervised neural net learning. IEEE Transactions on neural networks, 5(4), 537-550.
- Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.
- Fausser, S (2023). Artificial neural networks and classification metrics. Elearning University of Applied Sciences Neu-Ulm.
