# Leaf-Disease-Detection-

**Explainable Multimodal Deep Learning System for Leaf Disease Detection**

A cutting‑edge AI framework that combines visual, spectral, and environmental data to recognize and explain plant leaf diseases in real time.
Built with transformer‑based models, multimodal fusion, and Explainable AI (XAI) powered by GPT‑4.


**Overview**

Leaf disease detection is a growing field with applications in precision agriculture, crop protection, and smart farming.
Traditional unimodal approaches (only images or only sensor data) often fail in noisy, dynamic environments.

This project introduces a multimodal deep learning system that integrates:

  Images (leaf RGB photos) → Vision Transformer (ViT‑B/32)
  
  Spectral Data (infrared/hyperspectral cues) → CNN‑based spectral encoder
  
  Environmental Biometrics (temperature, humidity, soil moisture) → Normalized numerical features
  
All modalities are fused using LSTM + Dense layers, producing robust disease classification across 7 categories:

Healthy, Bacterial Spot, Early Blight, Late Blight, Leaf Mold, Septoria Leaf Spot, Mosaic Virus

To ensure transparency, predictions are explained in natural language using GPT‑4.

 **Key Features**
 
Multimodal Fusion: Image + Spectral + Environmental integration

Transformer‑based Feature Extraction: Vision Transformer for leaf images

Interactive Visualization: Real‑time disease distribution via Chart.js pie charts

Explainable AI (XAI): GPT‑4 generates human‑readable explanations for predictions

Real‑time Inference: Lightweight Flask REST API backend

Crop Adaptability: Extendable to new plant species, sensors, or contexts
