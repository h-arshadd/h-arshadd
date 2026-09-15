# Huda Arshad

Computer Science graduate building full-stack AI systems, from real-time computer vision to agentic LLM pipelines and production ML systems. First-authored research published at IEEE IBCAST 2025.

BS Computer Science · CGPA 3.73  
Currently exploring agentic AI: LLM agents layered over classical CS pipelines

[LinkedIn](https://linkedin.com/in/huda-a-bb4496319) · [Email](mailto:hudaarshad2004@gmail.com)

---

## Projects

**[Chain-Predict](https://github.com/h-arshadd/chain-predict)**
*Production-grade quantitative crypto trading platform · Built during ML internship*

End-to-end quantitative trading platform covering market data ingestion, technical and sentiment feature engineering, multi-model ML, strategy building, walk-forward backtesting, simulation, and live multi-wallet execution on Bybit. Built with a focus on preventing look-ahead bias and persisting strategy configuration, model runs, and trade history in PostgreSQL.

The ML pipeline supports classification, regression, and deep-learning time-series models, including XGBoost, LightGBM, CatBoost, N-BEATS, TCN, LSTM, and GRU. The platform also integrates TA-Lib technical indicators and Reddit sentiment using CryptoBERT. A FastAPI backend exposes the pipeline through domain-specific REST APIs, with a React/Vite dashboard for monitoring strategies, models, backtests, wallets, and executions.

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Pydantic` `Scikit-Learn` `XGBoost` `LightGBM` `CatBoost` `PyTorch` `Darts` `TA-Lib` `CryptoBERT` `PRAW` `React` `Bybit API`

**[Smart Surveillance & Attendance System](https://github.com/h-arshadd/faceattend-pro)**
*Final Year Project · Full-stack agentic AI system*

Real-time face recognition built on InsightFace (ArcFace) with cosine-similarity matching, reaching 95% recognition accuracy. Supports runtime user registration via webcam or image upload, with automatic augmentation and duplicate-face detection. No retraining required.

Two LLM agents using Llama 3.3-70B via Groq extend the system: an intruder detection agent that issues threat-level-classified security alerts, and a report assistant that answers natural-language attendance queries grounded in live attendance data.

`Python` `OpenCV` `InsightFace` `Streamlit` `Groq API` `LLMs` `Agentic AI`

**Agentic AI Timetable Generator**
*Hybrid symbolic + LLM system*

Autonomously generates conflict-free academic timetables by enforcing hard constraints symbolically, while using Gemini as a bounded reasoning module for ambiguous assignments. Accepts natural-language constraints and outputs a deterministically validated timetable in CSV format.

`Python` `Pandas` `Google Gemini API` `LLMs` `Constraint Solving`

**[E-Commerce Sales Predictor](https://github.com/h-arshadd/E-commerce_sales_predictor)**
*Full-stack machine learning web app*

Predicts product sales from pricing, discount, marketing spend, and customer segment. Built end-to-end with preprocessing, feature engineering, model training, evaluation, and a CRUD REST API for serving predictions.

`Python` `Flask` `Scikit-Learn` `Linear Regression` `REST API`

---

## Research

**Brain Tumor Cell Grading & Survival Prediction using MI-based Feature Selection and GenAI Approach**

*First author · IEEE IBCAST 2025 (International Bhurban Conference on Applied Sciences & Technology)*

A hybrid framework combining U-Net segmentation, GAN-based synthetic tumor generation, and MI-based feature selection for brain tumor grading and survival prediction on the BraTS 2022/23 dataset, achieving 96.5% classification accuracy and a C-Index of 0.89.

---

## Stack

### Languages

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

### AI / Machine Learning

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/-Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-337AB7?style=flat-square)
![LightGBM](https://img.shields.io/badge/-LightGBM-9ACD32?style=flat-square)
![CatBoost](https://img.shields.io/badge/-CatBoost-FFCC00?style=flat-square)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TA-Lib](https://img.shields.io/badge/-TA--Lib-1F425F?style=flat-square)

### Generative AI / NLP

![LLMs](https://img.shields.io/badge/-LLMs-412991?style=flat-square)
![Generative AI](https://img.shields.io/badge/-Generative%20AI-8E44AD?style=flat-square)
![Google Gemini](https://img.shields.io/badge/-Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![Groq](https://img.shields.io/badge/-Groq-F55036?style=flat-square)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/-Transformers-FFD21E?style=flat-square)

### Backend / APIs

![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/-REST%20APIs-02569B?style=flat-square)
![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-D71F00?style=flat-square)
![Pydantic](https://img.shields.io/badge/-Pydantic-E92063?style=flat-square)

### Databases

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### Frontend / Tools

![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/-Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
