# Maximal Marginal Relevance (MMR) for Search

This repository provides a practical implementation of Maximal Marginal Relevance (MMR) to enhance search result diversification. The primary goal is to re-rank search results, balancing relevance and diversity to avoid redundant information.

## Key Features

- **Text Embedding**: Utilizes `sentence-transformers` to generate dense vector representations of text data.
- **Similarity Search**: Performs semantic search by comparing query embeddings with document embeddings.
- **MMR Implementation**: Implements the MMR algorithm with sliding window to re-rank search results, improving diversity.
- **Jupyter Notebook**: A complete walkthrough of the process is available in `mmr.ipynb`.

## Dataset

The project uses the `COA_OpenData.csv` dataset, which contains product information from the Council of Agriculture.

_Data source: [https://data.gov.tw/dataset/43388](https://data.gov.tw/dataset/43388)_

## Getting Started

### Prerequisites

- Python 3.12 or higher

1. **Clone the repository:**
   ```bash
   gh repo clone boboru/maximal-marginal-relevance
   cd maximal-marginal-relevance
   ```

2. **Set up the environment and install dependencies using `uv`:**
   ```bash
   # Install dependencies from pyproject.toml
   uv sync
   ```

3. **Open `mmr.ipynb`** and run the cells to see the implementation in action.
