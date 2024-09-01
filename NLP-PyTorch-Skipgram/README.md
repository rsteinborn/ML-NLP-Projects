# Skip-Gram Model Implementation

This project implements the Skip-Gram model for word embeddings using PyTorch. It includes two separate implementations: one using the Reuters corpus and another using a custom corpus.

## Files

1. `MikolovEtAl_Reuters.ipynb`: Implementation using the Reuters corpus
2. `MikolovEtAl_CustomCorpus.ipynb`: Implementation using a custom corpus

## Features

- Implementation of the Skip-Gram model
- Negative sampling
- Word similarity calculations
- Analogy solving (CustomCorpus version)
- Evaluation of vector compositionality (CustomCorpus version)
- Visualization of word embeddings (CustomCorpus version)

## Requirements

- Python 3.x
- PyTorch
- NumPy
- NLTK
- SciPy
- Matplotlib (CustomCorpus version)
- Scikit-learn (CustomCorpus version)

## Usage

1. Open the desired Jupyter notebook (`MikolovEtAl_Reuters.ipynb` or `MikolovEtAl_CustomCorpus.ipynb`).
2. Run the cells in order to:
   - Import required libraries
   - Preprocess the data
   - Define and train the Skip-Gram model
   - Evaluate the model

## Key Components

- `SkipGramModel`: PyTorch module implementing the Skip-Gram architecture
- `generate_training_data`: Function to create training pairs
- `get_negative_samples`: Function for negative sampling
- `calc_mutual_information`: Function to calculate mutual information (Reuters version)
- `word_similarity`: Function to compute cosine similarity between word embeddings
- `solve_analogy`: Function to solve word analogies (CustomCorpus version)
- `evaluate_compositionality`: Function to evaluate vector compositionality (CustomCorpus version)
- `plot_embeddings`: Function to visualize word embeddings (CustomCorpus version)

## Limitations

- Reuters version: Limited computational resources restricted hyperparameter tuning and implementation of additional features.
- CustomCorpus version: The small custom corpus, while faster to train, lacks the size for advanced analogical tasks.

## Contributors

Reuters version:

- Raphael Steinborn
- Lidia Makishti
- Vineeth Racharla
- Saqib Sarwar

CustomCorpus version:

- Raphael Steinborn (Main Contributor)

## References

Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. arXiv preprint arXiv:1301.3781.
