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
1, Ensure you have Jupyter Notebook or JupyterLab installed.
2, Execute all cells in the notebook sequentially from top to bottom without skipping, to ensure all dependencies are loaded and each step is properly set up for the subsequent operations.

## Citation
1, C. Yin, R. Zhao, B. Qian, X. Lv and P. Zhang, "Domain Knowledge Guided Deep Learning with Electronic Health Records," 2019 IEEE International Conference on Data Mining (ICDM), Beijing, China, 2019, pp. 738-747, doi: 10.1109/ICDM.2019.00084. Repo: https://github.com/yinchangchang/DG-RNN/tree/master

2, Repo: https://github.com/sunlabuiuc/PyHealth/blob/4febba6061253c4c178fa035d2afa67e206fc9a8/pyhealth/medcode/pretrained_embeddings/kg_emb/examples/train_kge_model.py

