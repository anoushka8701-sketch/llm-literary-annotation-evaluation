# Evaluating Mistral 7B as a Literary Text Annotator

This project evaluates whether a locally deployed large language model can reliably classify tone and theme in Jack Kerouac's *Mexico City Blues*.

## Project Overview

I used Mistral 7B through Ollama to perform closed-set annotation across 244 choruses, using five tone categories and six thematic categories. Model outputs were evaluated against a 22-item human-annotated gold standard.

## Methods

- Local LLM deployment using Ollama
- Structured prompt design and JSON output parsing
- Human-versus-model annotation comparison
- Accuracy, precision, recall and F1 scores
- Cohen's kappa
- Confusion matrices and disagreement analysis

## Key Results

- Tone accuracy: 40.9%
- Tone Cohen's kappa: 0.261
- Theme accuracy: 59.1%
- Theme Cohen's kappa: 0.506

The results demonstrate that LLMs can identify some broad thematic patterns but struggle with ambiguity, literary devices and context-dependent tonal interpretation.

## Tools

Python, pandas, scikit-learn, Matplotlib, Seaborn, Ollama and Mistral 7B.

## Recognition

Completed as part of the MA Digital Humanities at King's College London. Awarded Distinction, with written feedback identifying potential for development into a conference or journal submission.
