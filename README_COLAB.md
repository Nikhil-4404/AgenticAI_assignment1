# RAG Assignment - Google Colab Version

## Project Overview
This version of the RAG Assignment is optimized for Google Colab. It creates the dataset and installs dependencies directly within the notebook environment, ensuring a zero-setup experience.

## Files
- **`rag_assignment_colab.ipynb`**: The standalone Jupyter Notebook containing the complete implementation (Data creation, RAG pipeline, Mock LLM).

## Instructions to Run
1. **Open Google Colab**: Go to [https://colab.research.google.com/](https://colab.research.google.com/).
2. **Upload Notebook**: 
   - Click **File > Upload notebook**.
   - Select the `rag_assignment_colab.ipynb` file from this folder.
3. **Run All Cells**:
   - Once opened, click **Runtime > Run all** in the top menu.
   - The notebook will automatically:
     - Install necessary libraries (`langchain`, `faiss-cpu`, etc.).
     - Create the sample `knowledge_base.txt` file.
     - Execute the RAG pipeline and show test results.

## Key Features
- **Zero Configuration**: No need to manually install Python or manage virtual environments.
- **Self-Contained**: The mock dataset is generated via code, so you don't need to upload external text files manually.
- **GPU Ready**: While this assignment runs fine on CPU, it is compatible with Colab's GPU runtime for faster embedding generation if needed.

## Dependencies
The notebook automatically installs the following via `pip`:
- `langchain`
- `langchain-community`
- `langchain-huggingface`
- `faiss-cpu`
- `sentence-transformers`
