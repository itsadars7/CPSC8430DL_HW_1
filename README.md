# Adarsha Neupane: Homework 1 – CPSC8430 Deep Learning

This repository contains the code for Homework 1 tasks


## Requirements
	•	Python >= 3.8
	•	PyTorch >= 1.12
	•	torchvision >= 0.13
	•	numpy
	•	matplotlib

Install dependencies with:
'''bash
pip install torch torchvision numpy matplotlib


## Dataset

The code uses CIFAR-10 from torchvision.datasets.
They will be automatically downloaded into ./data/ when running the scripts.
No manual download is required.


## How to Run

1. Open the corresponding notebook (e.g., HW1_GradientNorm.ipynb, HW1_MinimalRatio.ipynb, etc.).

2.	Run all cells in order. Each notebook has a main function or top-level execution block that will:
	•	Train the model(s) for the task
	•	Generate and save plots
	•	Print training progress and results


## Outputs

Each script automatically creates an output folder (e.g., HW_1-3_RandomLabels) and saves plots as .png files.
Figures generated from these outputs are included in the final report.


## Reproducibility
	•	Random seeds are fixed (set_seed) for reproducibility.
	•	If you want to run multiple random initializations, adjust the seed in the code.