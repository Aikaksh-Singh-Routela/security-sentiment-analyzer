# Security Sentiment Analyzer

Analyzes sentiment of cybersecurity news headlines (Positive/Negative/Neutral).

## Live Demo

Try the model here: [Security Sentiment Analyzer](https://huggingface.co/spaces/Aikaksh-Singh-Routela/security-sentiment-analyzer)

## Model on Hugging Face Hub

**Model Card & Files:** [Aikaksh-Singh-Routela/security-sentiment-model](https://huggingface.co/Aikaksh-Singh-Routela/security-sentiment-model)

You can use the model directly in Python:

```python
from transformers import pipeline

classifier = pipeline("text-classification", model="Aikaksh-Singh-Routela/security-sentiment-model")

result = classifier("Ransomware attack shuts down hospital systems")
print(result)
