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
excerpt: "Showcasing my AI/ML projects, research, and learning journey."
feature_row:
  - image_path: /assets/images/bert.jpg
    alt: "Agentic Chatbot"
    title: "Agentic Chatbot"
    excerpt: "Used TWCS + RCIS datasets to fine-tune BERT & smaller LLMs for customer intent and sentiment detection."
    url: "/projects/bert-airline"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/catboost.jpg
    alt: "Attrition Prediction"
    title: "Attrition Prediction using CatBoost"
    excerpt: "Built an explainable ML pipeline to predict employee attrition with SHAP-based feature importance."
    url: "/projects/catboost-attrition"
    btn_label: "Explore Project"
    btn_class: "btn--primary"
  - image_path: /assets/images/agentic.jpg
    alt: "Agentic AI"
    title: "Agentic AI for Airline Support"
    excerpt: "Developed multi-agent workflow (RouterAgent, BookingAgent, ComplaintAgent) with LangGraph + FastAPI."
    url: "/projects/agentic-ai"
    btn_label: "View Details"
    btn_class: "btn--primary"
---

{% include feature_row id="feature_row" %}
