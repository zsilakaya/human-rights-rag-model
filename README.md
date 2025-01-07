# A Dive into Human Rights and Law with an RAG and Question Answering System

## Project Overview
This repository contains the implementation of a **Retrieval-Augmented Generation (RAG)** and **Question Answering (QA)** system designed to parse and interpret historical legal documents, such as the Magna Carta. The system aims to assist students and educators by providing accurate, context-aware responses to queries about human rights and legal principles. The methodologies developed in this project can also be extended to other fields, such as medicine, to navigate complex information effectively.

## Objectives
This project aims to achieve the following:

1. **Semantic Splitting of Legal Texts:**
   - Experiment with various text chunking methods to determine the most effective way to semantically split legal texts:
     - **Recursive Character Text Splitter (Naive Chunking):** Divides text based on a fixed character count.
     - **Interquartile-Based Splitting:** Uses the interquartile range to define chunk sizes.
     - **Percentile-Based Splitting:** Splits text when sentence differences exceed a specific percentile.
     - **Manual Chunking:** Employs programmer-defined conditions for chunking.

2. **Embedding Model Integration:**
   - Select and implement an appropriate embedding model to process the semantically split text for further analysis.

3. **Construction of a RAG Model:**
   - Develop a Retrieval-Augmented Generation model by:
     - Integrating a pre-trained embedding model.
     - Processing text and storing it in a vector database for efficient retrieval.

4. **Creation of a Synthetic Dataset for Testing:**
   - Create a synthetic dataset to evaluate the performance of a Large Language Model (LLM) in understanding and responding to questions about human rights law.

## Significance
By achieving these objectives, the project contributes to the study and interpretation of legal texts, enhancing accessibility and comprehension of significant historical and legal documents. The methodologies and tools developed have practical applications in:
- **Legal Studies:** Assisting in the interpretation of dense legal texts.
- **Education:** Providing an interactive learning tool for students and educators.
- **Medicine:** Facilitating the navigation of medical journals and research papers.

## Team Members
- **Dinara Kurmangaliyeva**
- **Emel Safarini**
- **Zeynep Sıla Kaya**
- **Ruslan Nuriev**
- **Sezgi Cobanbas**
