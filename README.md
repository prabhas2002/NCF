# Neural Collaborative Filtering (NCF) on MovieLens Dataset

This repository contains the implementation of a Neural Collaborative Filtering (NCF) model trained on the MovieLens dataset. The model incorporates Generalized Matrix Factorization (GMF) and Multi-Layer Perceptron (MLP) to capture both linear and non-linear relationships.

## Overview

The NCF model is designed to provide accurate recommendations by leveraging the strengths of both GMF and MLP. The model was trained on the MovieLens dataset and achieved impressive performance metrics.

## Performance

- **HitRatio@10**: **0.70**
- **NDCG@10**: **0.42**

## Repository Structure

- `data_utils.py`: Contains utility functions for loading and preprocessing the dataset.
- `model.py`: Defines the NCF model architecture.
- `train.py`: Script for training the NCF model.
- `config.py`: Configuration file for specifying dataset paths and hyperparameters.

## Note:
This reposity is forked from https://github.com/guoyang9/NCF and the full credits goes to them only.
