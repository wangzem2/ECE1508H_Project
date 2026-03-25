# Explainability of Large Language Models for Classification Tasks
**Group 1**: Dongxuan Li, Zemeng Wang, Chaochen Zhang

## Project Overview
This project explores the interpretability of Large Language Models (LLMs). Using **GPT-2** as the base model, we implemented **LoRA** to fine-tune on the **CoS-E** dataset.

## Key Findings
- **Performance**: Accuracy increased from 0.16 to 0.36 via LoRA.
- **Ablation**: Identified **Rank r=8** as the optimal configuration.
- **CoT Insight**: Observed that Chain-of-Thought prompting can negatively impact small-scale models.

## Usage
All core logic is contained within `Project_Main.ipynb`.