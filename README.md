
# Making RAG Agents Repository

Welcome to the **Making RAG Agents** course! This repository contains all the materials you need to learn how to build Retrieval-Augmented Generation (RAG) agents using modern tools, frameworks, and large language models (LLMs). The course is structured into a series of Jupyter notebooks that walk you through theoretical concepts and practical implementations, culminating in a final assessment.

This course is made possible through resources and inspiration provided by **NVIDIA** and the **NVIDIA Deep Learning Institute (DLI)**.

## Table of Contents

- [Course Structure](#course-structure)
  - [Notebook 1: Course Environment](#notebook-1-course-environment)
  - [Notebook 2: LLM Services](#notebook-2-llm-services)
  - [Notebook 3: LangChain Expression Language](#notebook-3-langchain-expression-language)
  - [Notebook 4: Advanced Runnables and State Chains](#notebook-4-advanced-runnables-and-state-chains)
  - [Notebook 5: Document Loaders and Progressive Chunking](#notebook-5-document-loaders-and-progressive-chunking)
  - [Notebook 6: Embedding Models](#notebook-6-embedding-models)
  - [Notebook 7: Semantic Similarity and RAG Pipelines](#notebook-7-semantic-similarity-and-rag-pipelines)
  - [Notebook 8: Assessment and Final Exercise](#notebook-8-assessment-and-final-exercise)
- [Additional Topics](#additional-topics)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

---

## Course Structure

### Notebook 1: Course Environment
In this notebook, you will:
- Learn about the course environment, how it was created, and why it's structured this way.
- Understand how to use the **Jupyter Labs** interface to interact with the microservices via active network ports.

### Notebook 2: LLM Services
This notebook covers:
- **Pros and cons** of running LLM services locally versus in scalable cloud environments.
- Understanding the **AI Foundation Model Endpoint schemes**, including:
  - Low-level connection interfaces (e.g., via `curl` or `requests`).
  - Abstractions to integrate these interfaces with open-source frameworks like **LangChain**.
- How to retrieve LLM generations and select specific models to build your software.

### Notebook 3: LangChain Expression Language
In this notebook, you will:
- Learn how to leverage **chains** and **runnables** to orchestrate LLM-powered systems.
- Understand how to use LLMs for external conversations and internal reasoning.
- Build and run a simple **Gradio** interface within your notebook.

### Notebook 4: Advanced Runnables and State Chains
This notebook explores:
- Advanced orchestration of LLM systems using **runnables**.
- Utilizing **state chains** for dialog management and iterative decision-making.

### Notebook 5: Document Loaders and Progressive Chunking
Here, you will:
- Get familiar with **document loaders** and utilities for handling large documents.
- Learn to **chunk** documents for processing in limited context spaces and progressively build a knowledge base.
- Understand **recontextualization**, **coercion**, and **consolidation** in document handling.

### Notebook 6: Embedding Models
In this notebook, you'll explore:
- **Embeddings** — numerical representations of text — and how they help LLMs process semantic meaning.
- Apply embedding models for large-scale document processing, improving summarization and knowledge extraction.

### Notebook 7: Semantic Similarity and RAG Pipelines
This notebook covers:
- How **semantic similarity systems** facilitate efficient retrieval.
- Incorporating **retrieval modules** into your chat models to create a fully functional **RAG pipeline** for document retrieval and conversation memory.

### Notebook 8: Assessment and Final Exercise
For the final assessment, you will:
- Integrate techniques from previous notebooks to measure the effectiveness of your RAG pipeline.
- Submit the final coding component as part of the course's assessment.

---

## Additional Topics
- **Guardrails**: Implementing guardrails to ensure safe and reliable model outputs.
- **LangServe Routes**: Managing routes in **LangServe** to efficiently serve models to external applications.

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Jencheng1/RAGagents.git
   cd RAGagents
   ```

2. Install the required dependencies (see [Installation](#installation)).

3. Open the course notebooks in Jupyter Labs:
   ```bash
   jupyter lab
   ```

4. Follow the instructions provided in each notebook to complete the course.

---

## Installation

To set up the environment and install all dependencies:

1. Ensure you have Python 3.8+ installed.
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## Contributing

We welcome contributions to improve this course. Please follow the steps below:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin feature-branch`).
5. Create a Pull Request.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Credits

This course was developed with inspiration and resources from **NVIDIA** and the **NVIDIA Deep Learning Institute (DLI)**.

We are grateful for their contributions to the AI community and their support in providing cutting-edge learning materials.

---

Happy learning and building your RAG agents! If you have any questions, feel free to open an issue or contribute to the discussion.

--- 

