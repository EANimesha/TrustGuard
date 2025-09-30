# TrustGuard: IoT Intrusion Detection with XAI-Driven Feature Refinement for Enhanced Multi-class Edge Classification

### Overview
We propose a two-stage explainable Graph Neural Network (GNN) for IoT network intrusion detection. First, class-wise feature importance is extracted using post-hoc XAI on an E-GraphSAGE model. Then, these insights refine the feature space, and an updated E-GraphSAGE with a One-vs-All (OvA) classifier improves multi-class detection. Experiments on public IoT datasets show enhanced detection rates, F1-scores, 
and model interpretability, enabling transparent and targeted performance improvements.

![Architecture Diagram](https://github.com/EANimesha/TrustGuard/blob/main/Technical%20Work.jpg)

### Directory Structure 
- Trustguard_ACI_IoT_23.ipynb
- Trustguard_NF_ToN_IoT.ipynb
- Trustguard_Nf_BoT_IoT.ipynb
- Trustguard_Nf_BoT_IoT_v2_sample.ipynb
  
All the above Jupyter notebooks give the code and experimental results for the proposed approach, 'TrustGuard'. 

For each dataset, run experiments for:
- Performance Evaluation with E-GraphSAGE Detection Model
- Extracting E-GNNExplainer-based Insights from baseline model: Edge Importance and Edge Feature Importance
- Extracting E-PGExplainer-based Insights from baseline model: Edge Importance and Edge Feature Importance 
- Performance Evaluation with E-GraphSAGE Detection Model extended with One-vs-All (OvA) classifier and pruned less important features

### Dependencies
- python 3.9.2
- torch 2.3.1
- cuda 12.1
- DGL 2.4.0


