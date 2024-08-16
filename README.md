# PDFQuery_LangChain

This notebook demonstrates how to query PDF documents using the LangChain framework with Cassandra/AstraDB integration for vector-based retrieval. It provides a template for extracting relevant information from PDFs using advanced language models and database queries.

## Overview

The notebook is designed to perform the following tasks:

1. **Environment Setup**:
   - Import necessary libraries like `PDFQuery`, `LangChain`, and `AstraDB`.
   - Integrate the system with a Cassandra-based vector store to enable efficient document retrieval.

2. **Data Preprocessing**:
   - Load and preprocess PDF documents, converting them into a searchable format.
   - Use LangChain to generate embeddings from the document text, storing them in the vector store.

3. **Query Execution**:
   - Accept natural language queries from the user.
   - Process the query with LangChain, search the vector store for relevant document chunks, and return the most relevant content from the PDF.

4. **Output Display**:
   - Display the retrieved answers with relevance scores.
   - Support iterative querying for improved search accuracy.

## How to Use

1. **Install Dependencies**:
   - Ensure you have all the necessary libraries installed as mentioned in the notebook.

2. **Configure AstraDB**:
   - Add your AstraDB credentials for vector store configuration.

3. **Load PDF Documents**:
   - Use the provided functions to load and preprocess your PDFs.

4. **Execute Queries**:
   - Input your natural language queries to extract relevant information from the documents.

## Notebook Structure

- **Cell 1-4**: Import libraries and set up the environment.
- **Cell 5-7**: Define PDF query functions and integrate with LangChain.
- **Cell 8**: Execute the query and display results.
- **Cell 9-10**: Provide example queries and responses for demonstration.

## Use Cases

This notebook is particularly useful for:

- **Legal Document Review**: Quickly extract relevant clauses or information.
- **Financial Report Analysis**: Query specific financial metrics or statements.
- **Academic Research**: Extract key points or data from research papers.

Feel free to modify the notebook to suit your specific needs or extend its capabilities.

---

**Note**: Ensure you have access to an AstraDB instance for storing and querying the document embeddings.

