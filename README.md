# FedImp: Federated Learning Using Important Layers of Client Models for the Diagnosis of Breast Cancer Histopathology Images

## Introduction
Federated learning methods can utilize datasets from multiple clients without requiring data sharing, preserving privacy while leveraging a larger pool of data. FedImp is a novel federated learning method designed to utilize the important layers of client models for the diagnosis of breast cancer histopathology images. This approach adapts to data heterogeneity across clients and limits the deviation of client models from each other and from the aggregated model at the central server.

## Repository Structure
The repository has 8 folders named FedAdaGrad,FedAdam,FedAvg,FedAvgIVL,FedImp,FedImpAvg,FedProx,MOON. Each folder have 4 cilent file for local training & 1 server file for global averaging.

## Set parameters and paths:
Before running the code, ensure you set the appropriate parameters and paths in the respective client and server scripts.
