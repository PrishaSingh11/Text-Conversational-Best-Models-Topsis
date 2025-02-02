# Text-Conversational-Best-Models-Topsis

# Overview
This repository contains a TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) analysis performed on multiple Large Language Models (LLMs) to evaluate their performance based on various metrics. The models included in this study are:

- GPT-4
- Gemini 1.5 Pro
- Claude 2.1
- Llama 2
- MPT-30B

The evaluation is based on key metrics such as perplexity (PPL), BLEU score, ROUGE score, diversity metrics, latency, memory usage, and human evaluation scores.

## Files in This Repository

- **input_decision_matrix.csv** – The dataset containing performance metrics of different models.
- **text_coversational,py** – Jupyter Notebook containing the implementation of the TOPSIS method and visualization of results.
- **analysis.md** – Detailed analysis of the results, including rankings and insights.
- **visualisations** - Various Graphs
- **output_results.csv** - The output dataset

## Results Summary
Using the TOPSIS method, the models were ranked based on their closeness to the ideal solution. The final ranking is as follows:

1. **MPT-30B** (TOPSIS Score: 0.797322)
2. **Llama 2** (TOPSIS Score: 0.797322)
3. **Claude 2.1** (TOPSIS Score: 0.524829)
4. **Gemini 1.5 Pro** (TOPSIS Score: 0.513693)
5. **GPT-4** (TOPSIS Score: 0.421499)

From the results, **MPT-30B** and **Llama 2** are the best-performing models according to the TOPSIS method, with the highest scores.

## Visualization
The repository includes bar plots to visually represent the rankings of LLMs based on their TOPSIS scores.
