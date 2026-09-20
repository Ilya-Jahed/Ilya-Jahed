# Ilya Jahed

Computer Engineering undergraduate at the **Iran University of Science and Technology (IUST)**, working on **graph machine learning for network intrusion detection (NIDS)**.

- Research Assistant, [Scalable Systems Lab](https://ssl.iust.ac.ir/), IUST
- Teaching Assistant, Data Structures, IUST
- 🌐 [ilya-jahed.github.io](https://ilya-jahed.github.io) · open to research collaborations and graduate opportunities

## Research focus

I study how self-supervised graph neural networks can detect attacks in network traffic without relying on large labelled datasets. My interests are flow-level (edge-aware) representations, evaluation under previously unseen attack behaviour, and reproducible implementation and auditing of published methods.

**Current work.** My main project audits and extends **NEGSC**, a self-supervised graph-contrastive NIDS method for NetFlow data. The extension is private and under development; final architectural claims, results, and code are not yet public.

## Research path

I started with Anomal-E, moved to SL-GAD to understand graph anomaly detection more broadly, and then to NEGSC.

| Project | What it covers |
|---|---|
| [Anomal-E-Implementation](https://github.com/Ilya-Jahed/Anomal-E-Implementation) | Modular analysis of Anomal-E (edge-centric GNN with a DGI objective): separating the data pipeline, graph construction, encoder, and detectors; preprocessing and target-encoding concerns; faster graph construction on large NetFlow datasets. |
| [sl-gad-reimplementation](https://github.com/Ilya-Jahed/sl-gad-reimplementation) | Reimplementation of SL-GAD (generative + contrastive graph anomaly detection): random-walk subgraph sampling, multi-round scoring, and how node-centric anomaly detection differs from flow-level NIDS. |
| [negsc-nids](https://github.com/Ilya-Jahed/negsc-nids) | Modular reimplementation and audit of NEGSC (NEGAT encoder with Wasserstein and Gromov-Wasserstein losses), including the paper-vs-reference-code analysis and known discrepancies. |

Supporting material: [CS224W study notes](https://github.com/Ilya-Jahed/cs224w-study-notes) (graph ML) and [kernel-to-provenance-notes](https://github.com/Ilya-Jahed/kernel-to-provenance-notes) (Linux OS primitives for provenance-based intrusion detection).

These are reimplementations, audits, and study notes, not published results.

## Interests and tools

| | |
|---|---|
| Graph ML | GNNs, GraphSAGE, GAT, graph anomaly detection |
| Self-supervision | Contrastive learning, DGI, generative objectives |
| Security | NIDS, NetFlow analysis, provenance graphs |
| Implementation | Python, PyTorch, DGL, PyTorch Geometric |
| Systems | Linux, OS primitives |
