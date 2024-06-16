# Research_Paper_Skimmer :  Sequential Sentence Classification in Medical Abstracts

Welcome to SkimLit, an NLP project aimed at improving the readability of Randomized Controlled Trial (RCT) abstracts by classifying sentences into their respective roles (e.g., objective, methods, results, conclusions). This project replicates the deep learning model presented in the 2017 paper [PubMed 200k RCT: A Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071), leveraging the PubMed 200k RCT dataset to train and evaluate our models.

## Problem Statement

The increasing number of RCT papers, many of which lack structured abstracts, poses a challenge for researchers who need to quickly assess the literature. By classifying sentences within abstracts, we can transform unstructured text into a more accessible format, enabling researchers to skim through abstracts efficiently and focus on the most relevant sections.

## Solution

Creating an NLP model that classifies sentences in RCT abstracts into predefined categories (objective, methods, results, conclusions) to facilitate faster comprehension and navigation through medical literature.

## Project Outline

### Data Source

- **Dataset**: PubMed 200k RCT: A Dataset for Sequential Sentence Classification in Medical Abstracts

### Methodology

1. **Data Downloading**: Fetch the PubMed RCT200k dataset from GitHub.
2. **Preprocessing**: Implement a preprocessing function to prepare the dataset for modeling.
3. **Baseline Model**: Establish a baseline using a TF-IDF classifier.
4. **Deep Learning Models**: Experiment with various combinations of:
    - Token embeddings
    - Character embeddings
    - Pretrained embeddings
    - Positional embeddings
5. **Multimodal Model**: Build our first multimodal model, incorporating multiple types of data inputs, inspired by the architecture from [Neural Networks for Joint Sentence Classification in Medical Paper Abstracts](https://arxiv.org/abs/1612.05251).
6. **Error Analysis**: Identify the most incorrect predictions to refine our model.
7. **Wild Predictions**: Apply the model to PubMed abstracts from the wild to test its generalization.

## Resources

For a deeper understanding of the methodologies and concepts used in this project, refer to the following papers:

- [PubMed 200k RCT: A Dataset for Sequential Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071)
- [Neural Networks for Joint Sentence Classification in Medical Paper Abstracts](https://arxiv.org/abs/1612.05251)

## Zero to Mastery Deep Learning Course

This project was completed as part of the Zero to Mastery Deep Learning course, which provides comprehensive training in deep learning and natural language processing. The course offers practical, hands-on experience in building state-of-the-art models for various applications.

## Contributing

We welcome contributions to enhance the functionality and performance of the SkimLit project. Feel free to fork the repository, make improvements, and submit pull requests.
