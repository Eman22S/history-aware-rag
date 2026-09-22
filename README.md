# Retrieval-Augmented Generation (RAG) Workspace

This workspace is designed for implementing and experimenting with Retrieval-Augmented Generation (RAG) techniques. It includes scripts for data ingestion, retrieval, and generation, as well as advanced techniques like history-aware generation and hybrid search.


### Root Directory

- **`.env`**: Contains environment variables for configuration.
- **`history_aware_genaration.py`**: Script for history-aware generation.
- **`history-aware-RAG.webm`**: A demo or explanation of histor aware generation.
- **`ingestion_pipeline.py`**: Script for ingesting data into the system.
- **`retrieval_pipeline.py`**: Script for retrieving relevant data/documents.
- **`requirements.txt`**: Lists the dependencies required for the project.
- **`README.md`**: Documentation for the project.

### `db/` Directory

- **`chroma_db/`**: Contains the Chroma database files (e.g., `chroma.sqlite3`) for storing embeddings or other data.

### `docs/` Directory

- Contains various documents (e.g., PDFs and text files) that serve as a knowledge base for retrieval.


## Getting Started

1. **Install Dependencies**:
   Install the required libraries using the `requirements.txt` file:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

2. **Run Pipelines**:
    
   - To run the ingestion pipeline  ` python ingestion_pipeline.py`.
   - To run the retrieval pipeline `python retrieval_pipeline.py`.
   - To run the history aware chatbot ` python history_aware_genaration.py`.

3. **Explore Advanced Techniques**:
   Check the `rag-for-beginners/` directory for advanced RAG techniques.

## Dependencies

See the `requirements.txt` file for a list of required libraries.

## Video Walkthrough

- **File**: `history-aware-RAG.webm`
- [Watch the demo video](history-aware-RAG.webm)
- **Description**: This video demonstrates the history-aware generation process, showcasing how the system retrieves relevant information and generates context-aware responses.




## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
