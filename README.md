# Capstone

This repository contains two primary Jupyter Notebooks for analyzing citations in research papers:

1. **citationcontext.ipynb**
    - **Description:** Extracts citation contexts from PDF files and stores the results in a CSV file. The CSV includes the number of times a particular reference is cited, all citation contexts for each reference, along with the title of the paper and the author names.

2. **detection.ipynb**
    - **Description:** Finds whether a particular self-citation is essential or non-essential based on the citation context and summaries of the paper. This notebook requires the use of your own OpenAI API key.

## Dataset Availability

- The dataset required for this project has not been uploaded to the repository due to its large size. To obtain the dataset, please email me at [hmanojnarayan@gmail.com](mailto:hmanojnarayan@gmail.com).

## How to Use

### Environment Setup
- Ensure all required libraries are installed. 

    


### Running the Notebooks

1. **citationcontext.ipynb**
    - **Purpose:** Extracts citation contexts from PDF files.
    - **Instructions:**
        - Open the `citationcontext.ipynb` notebook in Jupyter Notebook or JupyterLab.
        - Execute the notebook cells sequentially to extract citation contexts and generate the `citation_contexts.csv` file.

2. **detection.ipynb**
    - **Purpose:** Detects anomalous self-citations based on extracted contexts and paper summaries.
    - **Instructions:**
        - Open the `detection.ipynb` notebook in Jupyter Notebook or JupyterLab.
        - Insert your OpenAI API key in the designated section of the notebook.
        - Execute the notebook cells sequentially to analyze and detect anomalous self-citations.
    
    **Note:** Replace the placeholder for the OpenAI API key with your actual key to enable the anomaly detection functionality.

### Results
- **citationcontext.ipynb:**
    - Outputs a CSV file (`citation_contexts.csv`) containing citation contexts, the number of citations per reference, paper titles, and author names.
  
- **detection.ipynb:**
    - Outputs an analysis indicating whether specific self-citations are essential or non-essential based on the provided contexts and summaries.

## Contact

For any queries or to request access to the dataset, please reach out to me at:

**Email:** [hmanojnarayan@gmail.com](mailto:hmanojnarayan@gmail.com)
