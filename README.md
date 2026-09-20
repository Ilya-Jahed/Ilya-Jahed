# Hi, I'm Ilya Jahed

Computer Engineering undergraduate at the **Iran University of Science and Technology (IUST)**, currently working on graph machine learning for network security and anomaly detection.

- GPA: **18.85/20**
- Research Assistant at the **Scalable Systems Lab, IUST**
- Teaching Assistant for **Data Structures**
- Main interests: graph learning, self-supervised learning, network intrusion detection, and graph anomaly detection

## Research Focus

My current research training focuses on understanding and evaluating graph-based methods for network intrusion detection.

I am particularly interested in:

- Graph Neural Networks and message passing
- Self-supervised and contrastive learning on graphs
- Flow-level and edge-aware network representations
- Network intrusion and anomaly detection
- Reproducible research and implementation auditing
- Evaluation under previously unseen attack behaviour

My main research project is based on auditing and extending **NEGSC**, a self-supervised graph-contrastive method for network intrusion detection on NetFlow data. The active extension work is currently private and under development; final architectural claims, results, and code are not yet public.

## Research Path

### Anomal-E

I began by analysing and modularising an implementation of **Anomal-E**, an edge-centric self-supervised GNN method for network anomaly detection.

This work included:

- Studying the paper and reference implementation
- Separating the data pipeline, graph construction, encoder, DGI objective, anomaly detectors, and evaluation
- Investigating preprocessing and target-encoding concerns
- Improving graph construction efficiency for large NetFlow datasets

[View the Anomal-E implementation](https://github.com/Ilya-Jahed/Anomal-E-Implementation)

### SL-GAD

I then studied and reimplemented **SL-GAD**, a node-centric graph anomaly-detection method combining generative and contrastive self-supervised learning.

This project helped me understand:

- Random-walk-based subgraph sampling
- Generative attribute reconstruction
- Multi-view contrastive learning
- Multi-round anomaly scoring
- The distinction between node-centric graph anomaly detection and flow-level NIDS

[View the SL-GAD reimplementation](https://github.com/Ilya-Jahed/sl-gad-reimplementation)

### NEGSC

I currently maintain a public modular reimplementation and audit of **NEGSC**, a graph-contrastive NIDS method using a NEGAT encoder with Wasserstein and Gromov-Wasserstein losses.

The public repository documents:

- The paper and reference notebook analysis
- Modular reconstruction of the training and inference pipeline
- Data and graph-processing decisions
- Known discrepancies between the paper and reference code

The independent extension work remains private and incomplete.

[View the NEGSC reimplementation and audit](https://github.com/Ilya-Jahed/negsc-fraud-detection)

## Selected Repositories

| Repository | Description |
|---|---|
| [Anomal-E-Implementation](https://github.com/Ilya-Jahed/Anomal-E-Implementation) | Modular analysis and reimplementation of Anomal-E |
| [sl-gad-reimplementation](https://github.com/Ilya-Jahed/sl-gad-reimplementation) | Reimplementation and study of SL-GAD |
| [negsc-fraud-detection](https://github.com/Ilya-Jahed/negsc-fraud-detection) | Public NEGSC reimplementation and code audit |
| [cs224w-study-notes](https://github.com/Ilya-Jahed/cs224w-study-notes) | Personal notes on Stanford CS224W and graph machine learning |
| [kernel-to-provenance-notes](https://github.com/Ilya-Jahed/kernel-to-provenance-notes) | Notes on OS primitives, provenance graphs, and systems security |

## Technical Interests

```text
Graph ML              GNNs, GraphSAGE, GAT, graph anomaly detection
Self-supervision      Contrastive learning, DGI, generative objectives
Cybersecurity         NIDS, NetFlow analysis, anomaly detection
Implementation        Python, PyTorch, DGL, PyTorch Geometric
Research practice     Reimplementation, auditing, ablation, reproducibility
Systems               Linux, OS primitives, provenance graphs
