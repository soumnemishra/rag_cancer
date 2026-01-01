# RAG Project

A Retrieval-Augmented Generation (RAG) project for cancer-related information.

## Project Structure

```
rag_cancer/
├── src/                    # Source code
│   ├── data_ingestion/    # Data loading and preprocessing
│   ├── embeddings/         # Embedding generation and management
│   ├── vector_store/       # Vector database operations
│   ├── retrieval/          # Retrieval logic
│   ├── llm/                # LLM integration and generation
│   ├── api/               # API endpoints and server
│   └── utils/             # Utility functions
├── config/                # Configuration files
├── data/                  # Data storage
│   ├── raw/              # Raw input data
│   ├── processed/        # Processed/cleaned data
│   └── vector_store/     # Vector database files
├── tests/                 # Test files
│   ├── unit/             # Unit tests
│   └── integration/      # Integration tests
├── scripts/               # Utility scripts
└── docs/                  # Documentation
```

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Configure your environment:
- Copy `config/config.example.yaml` to `config/config.yaml`
- Update with your API keys and settings

3. Run the application:
```bash
python src/api/main.py
```

## Usage

[Add usage instructions here]

