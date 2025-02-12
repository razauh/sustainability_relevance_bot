# Sustainability Relevance Bot

## Overview

The **Sustainability Relevance Bot** is a comprehensive machine learning project designed to predict the relevance of text to the **United Nations Sustainable Development Goals (SDGs)**. It utilizes the [EUR-Lex SDG-Annotated Dataset](https://huggingface.co/datasets/razaulhaq/eurlex_sdg_coverage) and implements various machine learning algorithms to classify legal texts based on their alignment with SDGs. 

Additionally, it features an interactive **Gradio-powered chatbot** that provides SDG relevance predictions for input text.

## Key Features

- **Multi-Label Classification:**  
  Implements multiple traditional machine learning algorithms for multi-label classification of SDGs.

- **Text Embedding with SentenceTransformers:**  
  Utilizes pre-trained sentence transformers (**all-MiniLM-L6-v2**) for generating text embeddings.

- **Best Model Selection:**  
  Automatically selects the best-performing model based on **micro-F1 score**.

- **Gradio-Powered Chatbot:**  
  Provides an interactive interface for predicting SDG relevance in new texts.

  ## Machine Learning Models

### Algorithms Implemented:

- **Bernoulli Naive Bayes**  
- **Random Forest Classifier**  
- **K-Nearest Neighbors (KNN)**  
- **Multi-Layer Perceptron (MLP)**  
- **Decision Tree Classifier**  
- **Extra Trees Classifier**  
- **HistGradient Boosting Classifier**  

### Best Performing Model:

- **K-Nearest Neighbors (KNN)** achieved the highest **micro-F1 score** of **0.9890**.

### Performance Metrics (KNN):

- **Micro Precision:** 0.9890  
- **Micro Recall:** 0.9890  
- **Micro F1 Score:** 0.9890  
- **Macro Precision:** 0.8995  
- **Macro Recall:** 0.8269  
- **Macro F1 Score:** 0.8594






 
