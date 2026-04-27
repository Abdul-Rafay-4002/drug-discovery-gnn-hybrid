# Hybrid Graph Neural Network for Drug Discovery

## Overview
This project implements a Graph Neural Network (GNN) based pipeline for molecular property prediction using the QM9 dataset. Additionally, a hybrid diffusion-inspired mechanism is proposed for molecular generation and optimization.

## Objective
- Predict molecular properties using GNNs
- Explore chemical space using hybrid generation
- Evaluate performance using regression metrics

## Dataset
- QM9 dataset (10,000 samples used for training subset)

## Model Architecture
- 3-layer Graph Convolutional Network (GCN)
- Global Mean Pooling
- Fully Connected Regression Layer

## Hybrid Approach
A diffusion-inspired mechanism is used to:
- Generate perturbed molecular graphs
- Score molecules using trained GNN
- Select top candidates for optimization

## Tech Stack
- Python
- PyTorch
- PyTorch Geometric
- NumPy
- Matplotlib

## How to Run

```bash
pip install -r requirements.txt
python src/train.py
python src/evaluate.py
