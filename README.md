# FedImp: Federated Learning Using Important Layers of Client Models for the Diagnosis of Breast Cancer Histopathology Images

## Introduction
Federated learning methods can utilize datasets from multiple clients without requiring data sharing, preserving privacy while leveraging a larger pool of data. FedImp is a novel federated learning method designed to utilize the important layers of client models for the diagnosis of breast cancer histopathology images. This approach adapts to data heterogeneity across clients and limits the deviation of client models from each other and from the aggregated model at the central server.

## Repository Structure
The repository has 8 folders named FedAdaGrad, FedAdam, FedAvg, FedAvgIVL, FedImp, FedImpAvg, FedProx, MOON. Each folder have 4 cilent file for local training & 1 server file for global averaging. Also 

## Set parameters and paths:
Before running the code, ensure you set the appropriate parameters and paths in the respective client and server scripts.

## Algorithms

- FedAvg and FedSGD (McMahan et al., 2016) [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629)
- FedProx (Li et al., 2018) [Federated Optimization in Heterogeneous Networks](https://arxiv.org/abs/1812.06127)
- FedOpt (FedAdam, FedYogi, FedAdaGrad) (Reddi et al., 2020) [Adaptive Federated Optimization](https://arxiv.org/abs/2003.00295)
- MOON (Qinbin Li et al., 2021) [Model-Contrastive Federated Learning](https://arxiv.org/abs/2103.16257)

## Model
We used the [Efficientnet-B3](https://arxiv.org/pdf/1905.11946) model in this experiment. Our final trained model is available at https://drive.google.com/file/d/195iMk_cuWJ-hlY5_sHSU8fjWDIOc5nqq/view?usp=sharing

## Datasets
We have used datasets from the following sources:

- #### BRACS: A Dataset for BReAst Carcinoma Subtyping in H&E Histology Images

Brancati, N., Anniciello, A. M., Pati, P., Riccio, D., Scognamiglio, G., Jaume, G., De Pietro, G., Di Bonito, M., Foncubierta, A., Botti, G., Gabrani, M., Feroce, F., & Frucci, M. (2021). BRACS: A Dataset for BReAst Carcinoma Subtyping in H&E Histology Images. ArXiv. /abs/2111.04740
- #### BreakHis: A Dataset for Breast Cancer Histopathological Image Classification

Spanhol, F. A., Oliveira, L. S., Petitjean, C., & Heutte, L. (2016). A Dataset for Breast Cancer Histopathological Image Classification. IEEE Transactions on Biomedical Engineering, 63(7), 1455-1462. doi: 10.1109/TBME.2015.2496264

## Metrics
- Area under ROC
