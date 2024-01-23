# Evaluating Large Language Models

This repository contains my individual project on evaluating language models (LMs). The project focuses on two tasks: Task A evaluates LMs' capabilities in natural language inference (NLI), and Task B explores biases in LMs related to sexual orientation.

For Task A, I tested four pre-trained models on the MultiNLI dataset to assess their performance in NLI. The results showed that 'nli-roberta-base' and 'nli-deberta-base' outperformed 'bert-large-uncased' and 'roberta-large'.

In Task B, I analyzed biases in LMs using the CrowS-Pairs dataset. BERT exhibited higher overall bias, while RoBERTa showed less bias and a greater tendency to favor sentences that counter stereotypes, particularly regarding sexual orientation.

For more information, please refer to the [full project report](MSBD5018_individual_ylye.pdf).

## Usage

To evaluate language models on natural language inference (NLI), you can use the provided script [Capabilities](Capabilities.ipynb). The repository includes the necessary code to preprocess the data and train and evaluate the models.

For bias detection within masked LMs, refer to [Risks](Risks.ipynb). You can follow the instructions in the repository to run the evaluation and analyze the results.



