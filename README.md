# Natural Language Processing Assignment

This repository contains the implementation and comparative analysis of several **Natural Language Processing (NLP) techniques** using Python. The project demonstrates core NLP concepts such as preprocessing, parsing, named entity recognition, word embeddings, and discourse analysis.

The experiments are implemented in a **Jupyter Notebook** and focus on understanding how different NLP algorithms work and how they compare in terms of accuracy, efficiency, and practical usability.

---

# Assignment Overview

Natural Language Processing enables computers to understand, analyze, and generate human language.
This assignment implements multiple NLP tasks and compares different techniques used in modern NLP systems.

assignment covers:

* Text preprocessing techniques
* Named Entity Recognition
* Part-of-Speech tagging
* Language models using N-grams
* Text cleaning approaches
* Syntax parsing algorithms
* Dependency parsing
* Probabilistic grammar models
* Word Sense Disambiguation
* Word embeddings
* Discourse segmentation
* Pronoun resolution (coreference)

Each section contains **implementation, explanation, and comparison** of the methods used.

---

# Repository Structure

```
NLP_Assignment
│
├── NLP_assignment.ipynb
│
└── README.md
```

### Main Notebook

`NLP_assignment.ipynb`

This notebook contains all experiments and explanations for the assignment.

---

# Implemented NLP Experiments

## 1. Stemming vs Lemmatization

A preprocessing application is implemented to transform words into their base forms.

Comparison focuses on:

* Accuracy of word normalization
* Computational efficiency
* Linguistic correctness

---

## 2. Named Entity Recognition (NER)

NER is applied to text to identify entities such as:

* Person
* Organization
* Location
* Date

Two approaches are compared:

* Rule-based NER
* Machine learning–based NER

---

## 3. Part-of-Speech Tagging and N-gram Models

A POS tagger assigns grammatical labels to words.

Example tags:

* Noun
* Verb
* Adjective
* Adverb

Language models are implemented using:

* **Unigram**
* **Bigram**
* **Trigram**

These models predict the **next word in a sentence**.

---

## 4. Text Cleaning Techniques

A regex-based system removes unwanted text patterns such as:

* URLs
* Emails
* Hashtags

This approach is compared with **tokenization-based cleaning** methods.

---

## 5. Sentence Parsing

Parsing techniques are applied to analyze grammatical structure.

The experiments examine:

* Parsing efficiency
* Handling syntactic ambiguity

---

## 6. CKY Parsing Algorithm

The **Cocke-Kasami-Younger (CKY)** algorithm is implemented for parsing **context-free grammars (CFGs)**.

Comparison is made between:

* CKY parsing
* Earley parsing

---

## 7. Dependency Parsing

Dependency parsing is used to extract **subject–verb–object relationships** in sentences.

Example:

Sentence
`John bought a laptop`

Extracted relations

Subject → John
Verb → bought
Object → laptop

This method is compared with **constituency parsing**.

---

## 8. Probabilistic Context-Free Grammars (PCFG)

PCFGs extend traditional CFGs by assigning probabilities to grammar rules.

This experiment compares:

* Deterministic CFG
* Probabilistic CFG

The results show how probabilities help handle ambiguity in sentence generation.

---

## 9. Word Sense Disambiguation (WSD)

WSD determines the correct meaning of ambiguous words based on context.

Example:

Word: **bank**

Possible meanings:

* Financial institution
* River bank

Two approaches are explored:

* Dictionary-based methods
* Machine learning-based methods

---

## 10. Word Embeddings

Word embeddings convert words into **numerical vector representations**.

The project explores embeddings generated using:

* **Word2Vec**
* **GloVe**

The embeddings are evaluated through **text classification tasks**.

---

## 11. Discourse Segmentation

A system is implemented to divide text into **coherent discourse units**.

Comparison is performed between:

* Rule-based segmentation
* Machine learning-based segmentation

---

## 12. Pronoun Resolution (Coreference Resolution)

This experiment resolves pronouns to their correct references.

Example:

Sentence:

```
John went to the store. He bought milk.
```

Resolution:

```
He → John
```

The project compares:

* Heuristic methods
* Deep learning approaches

---

# Technologies Used

* Python
* Jupyter Notebook
* Natural Language Processing techniques
* Regular Expressions
* Statistical Language Models

---

# How to Run the Project

### 1. Clone the repository

```
git clone https://github.com/Subhankar-choudhury/NLP_Assignment.git
```

### 2. Open the notebook

Open the notebook in:

* Jupyter Notebook
* JupyterLab
* Google Colab

```
NLP_assignment.ipynb
```

### 3. Run all cells

Execute the notebook sequentially to reproduce the results.

---

# Learning Outcomes

This project demonstrates practical implementation of several important NLP concepts:

* Text preprocessing
* Statistical language modeling
* Syntax parsing
* Semantic analysis
* Context understanding
* Representation learning

It provides a hands-on understanding of how modern NLP systems process and analyze human language.

---

# Author

Subhankar Choudhury

---

# License

This project is created for academic and educational purposes.
