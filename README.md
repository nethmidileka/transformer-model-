# Sinhala Mental Health Chatbot  

This repository contains the development process, experiments, and findings related to building a **Sinhala mental health chatbot**. The chatbot leverages various NLP techniques and deep learning models, including transformer-based architectures, to assist users in mental health discussions in Sinhala.  

---

## Table of Contents  
1. [Overview](#overview)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Challenges](#challenges)  
5. [Results](#results)  
6. [Future Improvements](#future-improvements)  
7. [How to Run the Project](#how-to-run-the-project)  
8. [License](#license)  

---

## Overview  
The goal of this project is to develop a chatbot capable of engaging in culturally sensitive and meaningful mental health conversations in Sinhala. Due to the scarcity of resources for low-resource languages like Sinhala, this project explores various machine learning and deep learning methods, with a focus on transformer models for NLP tasks.  

---

## Features  
- **Sinhala NLP Support**: Preprocessing techniques like lemmatization, segmentation, and stopword removal.  
- **Generative and Rule-Based Integration**: Combines transformer-based generative responses with a rule-based fallback mechanism.  
- **Mental Health Focus**: Provides responses tailored to mental health-related queries.  
- **Speech-to-Text Capability** (Planned): To support voice-based interactions.  
- **Multiplatform Support** (Planned): For mobile and web applications.  

---

## Technologies Used  
- **Programming Language**: Python 3.12.1  
- **Deep Learning Framework**: TensorFlow 2.17  
- **NLP Models**:  
  - Transformer-based model  
  - LSTM (previous experiment)  
- **Dataset**: 4,450 Sinhala question-answer pairs related to mental health  
- **Tools**: Google Colab, Git  

---

## Challenges  
1. **Data Scarcity**: Limited availability of annotated Sinhala datasets.  
2. **Cultural Nuances**: Mental health conversations require contextual sensitivity.  
3. **Model Performance**: Transformer-based model achieved a maximum accuracy of 47%, highlighting the challenges of training on low-resource languages.  
4. **Resource Constraints**: Memory and computational limitations during training.  

---

## Results  
- **Accuracy**: Transformer model peaked at 47%.  
- **Analysis**:  
  - Performance limited by data scarcity and the complexity of mental health conversations.  
  - The accuracy and loss curves (Figures 5.6 and 5.7) reveal areas for optimization.  

---

## Future Improvements  
1. **Data Augmentation**: To enrich the Sinhala dataset and improve model generalization.  
2. **Transfer Learning**: Fine-tuning domain-specific transformer models if available.  
3. **Hybrid Approach**: Enhancing chatbot performance by combining transformer models with more rule-based logic.  
4. **Multilingual Expansion**: Incorporating translations to extend usability to other languages.  
5. **Voice Support**: Adding speech-to-text integration for a voice-based chatbot.  

---

## How to Run the Project  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/sinhala-mental-health-chatbot.git  
   cd sinhala-mental-health-chatbot  

 
