# privacy-preserving fl

This repository provides implementation of privacy-preserving fl with lightweight differential privacy (DP),
zero‑knowledge proofs (ZK‑STARK). It focuses on measuring a comprehensive set of performance, fairness, scalability and transparency
and Excel export for analysis.

Note: This is a an implementation using [Flower](https://flower.dev) and TensorFlow, designed for research and experimentation.

## Overview

The code privacy-preserving fl with multiple clients training a CNN on the CIFAR‑10 and MNIST dataset and various metrics collected

- Communication overhead  
- Straggler effects  
- Fairness (equity, Jain’s index, relative deviation)  
- Bias (data, model, process)  
- Trust‑accuracy correlation 
- Convergence speed  
- Model complexity  
- Data heterogeneity 

All metrics are saved to an Excel file for further processing

## Requirements

Install the required packages using `pip`:
pip install flwr tensorflow numpy pandas matplotlib seaborn scipy openpyxl xlsxwriter
