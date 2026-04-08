# Explainability of Large Language Models for Classification Tasks
> **Note on Notebook Preview:** Due to the large file size and interactive widgets like tqdm, GitHub's native viewer may occasionally fail to render the `.ipynb` file. 
> If you encounter a "Large diffs" or "Invalid Notebook" error, please download the file and open it locally via Jupyter/VS Code.

**Group 1**: Dongxuan Li, Zemeng Wang, Chaochen Zhang

## Project Overview
This project explores the interpretability of Large Language Models (LLMs). Using **GPT-2** as the base model, we implemented **LoRA** to fine-tune on the **CoS-E** dataset.

## Key Findings
- **Performance**: Accuracy increased from 0.16 to 0.36 via LoRA.
- **Ablation**: Identified **Rank r=8** as the optimal configuration.
- **CoT Insight**: Observed that Chain-of-Thought prompting can negatively impact small-scale models.

## Project Structure
* `Group1_Project_Main.ipynb`: The core notebook containing all 8 modules (Training, Evaluation, CoT, and Error Analysis).
* `lora_gpt2_cose_ckpt/`: In Weight_and_Results_of_ThreeModels folder: LoRA fine-tuned weights for the base model.
* `lora_gpt2_cose_cot_ckpt/`: In Weight_and_Results_of_ThreeModels folder: LoRA fine-tuned weights using Chain-of-Thought prompting.
* `lora_rank_ablation_outputs/`: In Weight_and_Results_of_ThreeModels folder: Results and logs for the LoRA Rank ablation study ($r=4, 8, 16$).
* `baseline_gpt2_cose_ckpt`: : In Weight_and_Results_of_ThreeModels folder: Weights and results for the baseline model.
* `requirements.txt`: Environment dependencies.
* `main_comparison_results.csv`: In Doc folder: Final test results comparision. 
