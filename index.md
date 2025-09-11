---
layout: splash
title: "Welcome to My AI/ML Portfolio"
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/ai-banner.jpg
  actions:
    - label: "About Me"
      url: "/about/"
    - label: "Projects"
      url: "/projects/"
excerpt: "I specialize in AI, Machine Learning, and Data-driven solutions, with experience spanning research, model development, and real-world applications.
This portfolio highlights my projects, case studies, and ongoing work, reflecting my skills and growth in the AI/ML domain."

feature_row1:
  - image_path: /assets/images/chatbot.png
    alt: "Agentic Chatbot"
    title: "Airlines Conversational Agentic Chatbot"
    excerpt: "Multi-Agentic Workflow for customer support and self service for airlines agent"
    url: "https://github.com/Bluthunder/Agentic-Chatbot"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/bike.png
    alt: "Bike Rental Prediction"
    title: "Bike Rental Prediction"
    excerpt: "A Machine Learning model training and deployment pipeline for a Bike Share Rental System. This project automates the entire ML workflow, from training to API deployment using GitHub Actions, FastAPI, Docker, and Pytest."
    url: "https://github.com/Bluthunder/BIKESHARE_PROJECT"
    btn_label: "Read More"
    btn_class: "btn--primary"
    
  - image_path: /assets/images/housing.png
    alt: "Housing prediction Model"
    title: "Housing Prediction Model Training"
    excerpt: "A Machine Learning model training and deployment pipeline for a Housing prediction System. This project automates the entire ML workflow, from data preprocessing to model training and saving to model registry using GitHub Actions."
    url: "https://github.com/Bluthunder/Housing-Prediction-Model"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path:


feature_row2:
  - image_path: /assets/images/finetuning.png
    alt: "FineTuning"
    title: "LLM Finetuning airlines domain"
    excerpt: "Fine-tuning Mistral-7B with PEFT and QLoRA for domain adaptation in the airline industry. This project focuses on enhancing both NLG and NLU tasks, enabling more accurate and context-aware conversational AI for airline-specific use cases."
    url: "https://github.com/Bluthunder/ConversationAgent-Finetuning-Pipeline"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/dataops.png
    alt: "DataOps"
    title: "Data Ops Pipeline for fine tuning"
    excerpt: "Automated DataOps pipeline for cleaning and preprocessing conversational datasets (TWCS, Convo3K, etc.) from S3. Transforms raw data into chat-style format, generates NLG and NLU splits, and stores processed outputs in structured S3 buckets."
    url: "https://github.com/Bluthunder/ConversationalAgent-DataPipeline"
    btn_label: "Read More"
    btn_class: "btn--primary"

  - image_path: /assets/images/image.png
    alt: "ImageClassifier"
    title: "Image classficiation model using Pytorch"
    excerpt: "Image classification model built with PyTorch and trained on the ImageNet dataset, demonstrating deep learning for large-scale visual recognition."
    url: "https://github.com/Bluthunder/ImageClassification"
    btn_label: "Read More"
    btn_class: "btn--primary"


---

{% include feature_row id="feature_row1" %}
{% include feature_row id="feature_row2" %}