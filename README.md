# Optuna Hyperparameter Tuning & Neptune Integration for Regression Models using LightGBM

This repository demonstrates how to combine **Optuna** for hyperparameter optimization, **LightGBM** for regression modeling, and **Neptune.ai** for experiment tracking. The goal is to streamline model experimentation, automatically log key metadata, and monitor training performance in real time.

---

## Table of Contents

- [Overview](#Overview)
- [Features](#Features)
- [Installation](#Installation)

- [Documentation](#Documentation)
- [License](#License)
- [Acknowledgments](#Acknowledgments)

---

## Overview

**Optuna** is an automatic hyperparameter optimization framework that uses a _define-by-run_ interface, integrating seamlessly with modern ML workflows.

**LightGBM** is a high-performance gradient boosting framework using tree algorithms, optimized for speed and large datasets.

**Neptune.ai** serves as an experiment tracking and model registry platform. Its integration with LightGBM and Optuna allows for automatic metadata logging without manual setup.

---

## Features

With Neptune–LightGBM integration, the following metadata is logged automatically:

- Training and validation metrics
- Model hyperparameters
- Dataset info: feature names, number of features, number of rows
- Hardware consumption metrics: CPU, GPU, memory usage
- Standard output and error streams
- Training code and Git commit info

Neptune–Optuna integration logs:

- Trial parameters and objective values
- Optimization history and Pareto fronts
- Study progress and parameter importance visualizations

---

## Installation

Install all required packages:



```bash

neptune                       1.10.4
neptune-lightgbm              2.0.0
neptune-optuna                1.2.0

pip install neptune neptune-lightgbm neptune-optuna
```

---

## Documentation

For more details, visit:  
[Neptune-LightGBM Integration Documentation](https://docs.neptune.ai/integrations/lightgbm/)

---

## License

Released under the MIT License.

---

## Acknowledgments

- [Optuna](https://optuna.org/)  
- [LightGBM](https://github.com/microsoft/LightGBM)  
- [Neptune.ai](https://neptune.ai/)


