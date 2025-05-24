# Ksi-Centrality: Implementation and Benchmarking

This repository provides an implementation of the ksi-centrality and normalized ksi-centrality measures as introduced in the paper:

> **New centrality measure: ksi-centrality**  
> Mikhail Tuzhilin, March 2025  
> [arXiv:2503.02488](https://arxiv.org/abs/2503.02488)

## About

Ksi-centrality is a novel graph centrality metric that evaluates the importance of a node based on the significance of its neighbors. The normalized version exhibits properties akin to the local clustering coefficient and effectively differentiates between real-world and synthetic networks.

## Features

- Efficient computation of ksi-centrality and normalized ksi-centrality
- Support for both dense (`numpy`) and sparse (`scipy.sparse`) adjacency matrices
- Benchmarking on synthetic graphs (e.g., Barabási–Albert model) and real-world datasets (e.g., Facebook subgraphs)

## 📄 Overview

All code, including implementation, data loading, and visualization, is contained within the Jupyter notebook:

- [`ksi.ipynb`](ksi.ipynb): Contains the full implementation of ksi-centrality measures, data processing, and analysis.

## 📊 Datasets

- **Synthetic Graphs**: Generated using models like Barabási–Albert to test scalability and behavior.
- **Real-World Graphs**: For instance, `facebook_s1` from the [Network Repository](https://networks.skewed.de/net/facebook_organizations), representing a subset of the Facebook social network.

> Note: Ensure compliance with the licensing terms of any included datasets.

## 📝 License

This project is licensed under the MIT License. Refer to the [LICENSE](LICENSE) file for details.
