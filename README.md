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
The main notebook containing the final version of the project code is [DL4H_Team_38_Final_Project.ipynb](https://github.com/likaikl2/DLH_Team38_Final/blob/main/DL4H_Team_38_Final_Project.ipynb). This notebook includes the data preprocessing, model architecture, training loop, and evaluation metrics.

### Running in Google Colab

The recommended way to run this project is using Google Colab, which provides free access to GPUs. Here's a step-by-step guide:

1. Open the `DL4H_Team_38_Final_Project.ipynb` notebook in Google Colab by clicking  <a target="_blank" href="https://colab.research.google.com/github/likaikl2/DLH_Team38_Final/blob/main/DL4H_Team_38_Final_Project.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>  button.

2. Make sure the runtime type is set to "GPU" for optimal performance:
   - Click on the "Runtime" menu and select "Change runtime type".
   - Choose "GPU" from the "Hardware accelerator" dropdown.
   - Click "Save".

3. Execute the notebook cells in order by clicking on the "Runtime" menu and selecting "Run all". This will run the entire pipeline, from data loading to model evaluation.

The notebook should take approximately 45-60 minutes to run on a Tesla T4 GPU instance with 50 training epochs. If you run it on a CPU instance, expect the training to take around 8-10 times longer.


### Running Locally
If you prefer to run the code locally, follow these steps:

1. Clone this repository to your local machine using `git clone`.

2. Navigate to the project directory.

3. Launch Jupyter Notebook or JupyterLab.

4. Open the `DL4H_Team_38_Final_Project.ipynb` notebook.

5. Run the notebook cells in order.

Note that running the code locally requires a GPU for optimal performance. If you don't have access to a GPU, you can still run the code on a CPU, but training will take significantly longer.

## Citation
1. C. Yin, R. Zhao, B. Qian, X. Lv and P. Zhang, "Domain Knowledge Guided Deep Learning with Electronic Health Records," 2019 IEEE International Conference on Data Mining (ICDM), Beijing, China, 2019, pp. 738-747, doi: 10.1109/ICDM.2019.00084. Repo: https://github.com/yinchangchang/DG-RNN/tree/master

2. Repo: https://github.com/sunlabuiuc/PyHealth/blob/4febba6061253c4c178fa035d2afa67e206fc9a8/pyhealth/medcode/pretrained_embeddings/kg_emb/examples/train_kge_model.py

