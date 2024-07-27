# GenAI - Policy Document generative search application

## Overview
The objective of this project is to develop an efficient system for parsing, indexing, and querying information from an HDFC Policy PDF document using LlamaIndex. The solution aims to facilitate the swift and accurate retrieval of policy details based on user queries, ensuring that users can easily access and understand specific policy information.

## Project Goals
- Parse the HDFC Policy PDF to extract relevant information.
- Index the extracted data for efficient querying.
- Handle user queries and provide relevant information from the policy document.
- Evaluation
  
## Design choice
LlamaIndex is chosen for its capability to handle document parsing, indexing, and querying efficiently and it specialized for search and retrieval tasks.Evaluation and benchmarking are crucial in the development of large language models (LLMs) applications. LlamaIndex can autonomously generate questions from your data, facilitating an evaluation pipeline for RAG applications.  The evaluation in LlamaIndex is categorised into two main types: Response Evaluation and Retrieval Evaluation.
![image](https://github.com/user-attachments/assets/e7c22777-341b-4d2c-b350-43479b44740b)

## Challenges
**Complexity of PDF Documents**: Insurance policies are often lengthy and contain complex structures such as tables, sections, and nested clauses, which can make it difficult for the indexer to parse and understand.
**Contextual Retrieval:** Insurance policies often require context to fully understand the meaning of specific clauses or terms, which can be difficult for a retrieval system to handle.
**Indexing Efficiency:** Indexing large policy documents or multiple documents can be resource-intensive and time-consuming, leading to performance issues.
**User Query Interpretation:** Users might phrase queries in various ways, and interpreting these queries accurately can be challenging.


## Requirements
- Python 3.9+
- LlamaIndex
- OpenAI
- pandas
- tqdm

