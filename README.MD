# Workshop on Machine Learning Techniques at IBEC

The workshop consisty of three parts represented by one respective notebook.
- Visualise the BBBP dataset using Uniform Manifold Approximation and Projection (UMAP)
- Segmenting and Classification of cell images using Random Forest Classification (RFC)
- Categorisation of cell images using a Convolutional Neural Network



## Usage
Choose one of the two options (A or B) to participate in this workshop.

### A: Participate with Google Colab
For this a Google account is necessary.

1. Notebook 1: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XSCNLfT-r_jLDaBekB_Oe0FVkx_EZftW?usp=sharing)
2. Notebook 2: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1XbiIPbmav-w89CQHtyFpTqIwYM67QJtz?usp=sharing)
3. Notebook 3: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14B8RAfnoQSmxN52NzmOIfxecHMa0_rKB?usp=sharing)

### B: Participate with your own computer
To use and run the notebooks on your Computer, follow these steps:
1. **Clone or Download the Repository**  
    You can either clone this repository using Git or download it as a ZIP file:  
    - To clone using Git, run the following command:  
      ```bash
      git clone <repository-link>
      ```  
    - Alternatively, download the repository as a ZIP file from the GitHub webpage and extract it to your desired location.

2. **(Optional) Download the Training Data**  
    The data for training the models is too large to be stored in this repository. Please download the data from [Kaggle - Blood Cell Images](https://www.kaggle.com/datasets/paultimothymooney/blood-cells) and extract it into the repository folder if you want to train the models yourself and run all sections of the third notebook.

3. **Set Up the Python Environment**  
    It is recommended to use a Python virtual environment to manage dependencies. Follow these steps:

    - **Create a Virtual Environment**  
      Run the following command in the folder that contains the repository to create a virtual environment:
      ```bash
      python -m venv .venv
      ```
      
    - **Activate the Virtual Environment**  
      - On Windows:
         ```bash
         .venv\Scripts\activate
         ```
      - On macOS/Linux:
         ```bash
         source .venv/bin/activate
         ```

    - **Install Dependencies**  
      Install the required Python packages using the `requirements.txt` file:
      ```bash
      pip install -r requirements.txt
      ```

4. **Run the Notebooks**  
    Start Jupyter Notebook to run the notebooks:
    ```bash
    jupyter notebook
    ```