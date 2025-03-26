# Workshop on Machine Learning Techniques at IBEC

The workshop consisty of three parts represented by one respective notebook.
- Visualise the BBBP dataset using Uniform Manifold Approximation and Projection (UMAP)
- Segmenting and Classification of cell images using Random Forest Classification (RFC)
- Categorisation of cell images using a Convolutional Neural Network



## Usage
Choose one of the two options (A or B) to participate in this workshop.

### A: Participate with google colab
For this a Google account is necessary.

1. Notebook 1: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lM2Ty-ZlaoztyLCAmt7ECoaTehIAFZCV?usp=sharing)
2. Notebook 2: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17p9XR8kuWuSdm2eOkgIFS_RuyCxFtgSh?usp=sharing)
3. Notebook 3: [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HkEGZOofBMUs8y0WJez6TKBYVUZ0uEWb?usp=sharing)

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
    The data for training the models is too large to be stored in this repository. Please download the data from [this link](<placeholder-link>) and extract it into the repository folder if you want to train the models yourself.

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

    - **(Optional) Using a Local Python Installation**  
        If you prefer not to use a virtual environment, ensure that your local Python installation has all the required dependencies. Install them using:
        ```bash
        pip install -r requirements.txt
        ```

4. **Run the Notebooks**  
    Start Jupyter Notebook to run the notebooks:
    ```bash
    jupyter notebook
    ```

6. **Deactivate the Virtual Environment (if used)**  
    Once you are done, deactivate the virtual environment by running:
    ```bash
    deactivate
    ```