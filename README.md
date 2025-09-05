# Few-Shot Prompt for Sentiment Scoring

This repository contains the **few-shot prompt** used in our research for extracting sentiment scores from **financial news articles** with large language models (LLMs), along with the results of our comparative analysis.

## Contents

- `fewshot_prompt.txt` → The prompt template used for all experiments.
- `Delta Analysis.png` → Visualization of the delta analysis comparing our silver label (GPT-4o) with the four selected LLMs (LLaMA, Mistral, Qwen, DeepSeek).

## Usage

The prompt was provided as input to **four different LLMs** (LLaMA, DeepSeek, Mistral, Qwen) to evaluate their ability to classify and extract sentiment in financial news.

- Each model received the **same prompt**.
- Outputs were compared against our **silver label** (GPT-4o).
- We performed **delta analysis** to quantify differences between GPT-4o scores and those produced by the other LLMs.

## Notes

- Shared for **review purposes only** as part of a conference submission.
