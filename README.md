# Information-Retrieval-with-Generative-Models

## Final Project for DS8008 - NLP
### Contributors

This project was made possible by the hard work and dedication of the following individuals:

- [Sarbpreet Ghotra](https://github.com/sarbghotra)
- [Sameer Ladha](https://github.com/sameerladha)

### Overview

This repository contains the research and implementation code for comparing various document retrieval models, focusing on the effectiveness of the Retrieval-Augmented Generation (RAG) model, BERT model, Sparse Model using Pyserini, and Dense Model using Dense Passage Retrieval (DPR). Our goal is to evaluate each model's capacity to retrieve relevant documents based on specific queries, aiming to enhance the efficiency and accuracy of information retrieval systems.

### Models Explored

- **Retrieval-Augmented Generation (RAG) Model**: Integrates retrieval and generative components for improved response accuracy and relevance.
- **BERT Model**: Utilizes the BERT model for advanced text processing and classification.
- **Sparse Model (Pyserini)**: Employs sparse retrieval techniques for efficient document retrieval.
- **Dense Model (DPR)**: Uses dense vector space to enable nuanced and semantically rich retrieval capabilities.

### Dataset

The **Microsoft Research WikiQA Corpus** was used for this project. It's a publicly available dataset designed for open-domain question answering research, consisting of question and sentence pairs derived from Bing query logs.

### Problem Description

In the realm of document retrieval, efficiently sourcing relevant documents in response to user queries remains a significant challenge. Traditional retrieval methods and Large Language Models (LLMs) have shown limitations in accuracy, speed, and contextual understanding.

### Context

With the exponential growth of digital information, the need for advanced retrieval systems that can navigate vast datasets with high precision and relevance has become paramount. Traditional sparse retrieval techniques, while efficient, often fall short in understanding the semantic nuances of queries. Dense retrieval methods offer improvements in semantic understanding but come with increased computational demands.

### Limitations of Other Approaches

- **Sparse Retrieval Techniques**: Struggle with semantic query understanding, leading to less relevant results.
- **Dense Retrieval Methods**: Offer better semantic understanding but at the cost of higher computational resources.
- **LLMs**: While powerful in generating responses, they require extensive data preparation and can be prone to generating outdated or incorrect information.

### Our Solution

Our research explores the integration of retrieval and generative components through models like the Retrieval-Augmented Generation (RAG) model, alongside comparisons with BERT, Sparse Model using Pyserini, and Dense Model using DPR. Our approach aims to:

- Enhance retrieval accuracy by combining the strengths of sparse and dense retrieval techniques.
- Improve response relevance and contextual understanding using generative models.
- Address computational and resource limitations by exploring efficient implementation strategies.

This project contributes to the ongoing evolution of information retrieval systems, aiming for a balance between precision, recall, and computational efficiency.
