# DLH_Team38_Final

# CS 598 Deep Learning for Healthcare: Final Project

## Authors
Eric Chen(echen40), Li-Kai Lin(likaikl2), Peng-Yuan Huang(pyh2)

## Description
The goal of this study is to predict heart failure risk in patients based on their electronic health record (EHR) data. Early identification of high-risk patients could enable timely interventions and improved outcomes. However, accurately predicting heart failure risk remains challenging, especially when EHR data is limited. This study aims to validate whether the Domain Knowledge Guided Recurrent Neural Networks (DG-RNN) model, which incorporates medical domain knowledge via a knowledge graph and utilizes various architectural components, can outperform existing risk prediction models and provide interpretable results.


## Prerequisites
Before running this notebook, ensure you have the following packages installed or follow the notebook code cell sequence running from top to bottom:
- Python 3.10
- NumPy
- Pandas
- Pytorch
- PyHealth
- Matplotlib
- Scikit-learn

## Dataset

The dataset used in this project is the MIMIC-III dataset.

## Usage
To run this notebook:
1. Ensure you have Jupyter Notebook or JupyterLab installed.
2. Installation:
   - Install Python on your computer if you haven't already. You can download it from the official Python website (https://www.python.org).
   - Install Jupyter Notebook using pip, the Python package installer. Open a terminal or command prompt and run the following command:
     ```
     pip install jupyter
     ```

    
3. Starting Jupyter Notebook:
   - Open a terminal or command prompt.
   - Navigate to the directory where you want to create or access your Jupyter Notebook files.
   - Run the following command to start Jupyter Notebook:
     ```
     jupyter notebook
     ```
   - This will start the Jupyter Notebook server and open a web browser window with the Jupyter Notebook interface.

  
4. Open the notebook and execute all cells in the notebook sequentially from top to bottom without skipping, to ensure all dependencies are loaded and each step is properly set up for the subsequent operations.
   ```
   "Shift + Enter": Run the current cell and move to the next cell.
   "Ctrl + Enter" (or "Cmd + Enter" on macOS): Run the current cell and stay in the same cell.
   "Alt + Enter": Run the current cell and insert a new cell below.
   "Esc": Enter command mode (used for cell-level actions).
   "Enter": Enter edit mode (used for editing cell contents).
   ```


5. Exporting Notebooks: To export your notebook to other formats like HTML, PDF, or Python script, go to the "File" menu and select "Download as". Choose the desired format from the dropdown menu, and the notebook will be downloaded to your computer.

6. Shutting Down Jupyter Notebook: To shut down Jupyter Notebook, save your work and close the browser tabs. In the terminal or command prompt where you started Jupyter Notebook, press "Ctrl + C" twice to stop the Jupyter Notebook server.

## Citation
1. C. Yin, R. Zhao, B. Qian, X. Lv and P. Zhang, "Domain Knowledge Guided Deep Learning with Electronic Health Records," 2019 IEEE International Conference on Data Mining (ICDM), Beijing, China, 2019, pp. 738-747, doi: 10.1109/ICDM.2019.00084. Repo: https://github.com/yinchangchang/DG-RNN/tree/master

2. Repo: https://github.com/sunlabuiuc/PyHealth/blob/4febba6061253c4c178fa035d2afa67e206fc9a8/pyhealth/medcode/pretrained_embeddings/kg_emb/examples/train_kge_model.py

