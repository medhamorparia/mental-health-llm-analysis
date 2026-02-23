# mental-health-llm-analysis

Mental Health Disorder Detection Using Transformer Models

This project investigates the effectiveness of transformer-based language models in detecting mental health conditions from social media text.

Models used:
- DistilBERT
- MentalBERT

Datasets:
### Twitter Mental Health Dataset

Shing, Han-Chin and Nair, Varun and Zirikly, Ayah. (2022).  
**An Extensive Multi-Disorder Mental Health Dataset from Twitter.**  
Zenodo.  
DOI: https://doi.org/10.5281/zenodo.6409736  
Link: https://zenodo.org/records/6409736  

This dataset contains Twitter posts labeled for multiple mental health conditions and was used to evaluate model performance on short-form social media content.

### Reddit Mental Health Dataset

Murarkar, Amol and collaborators. (2021).  
**Mental Health Classification using Social Media Text.**  
GitHub Repository.  
Link: https://github.com/amurark/mental-health-classification  

This dataset contains Reddit posts labeled for mental health classification and provides longer-form text compared to Twitter.

Goals:
- Compare performance between general-purpose and domain-specific models
- Evaluate effectiveness across platforms

Methods:
- Fine-tuned transformer models using HuggingFace Transformers
- Evaluated accuracy, precision, recall, F1 score

Results:
MentalBERT showed stronger performance on Reddit data, suggesting domain-specific pretraining improves classification of mental health language.

Tools:
- Python
- PyTorch
- HuggingFace Transformers
- Google Colab

This repository also includes a short research paper based on this project:

Mental_Health_LLM_Analysis_Paper.pdf

This paper was written as part of a course research project with a collaborator.

My primary contributions included:

- Implementing and fine-tuning the transformer models
- Running experiments and collecting results
- Contributing to analysis and interpretation of model performance
- Assisting with writing the methods and results sections

Author: Medha Morparia
