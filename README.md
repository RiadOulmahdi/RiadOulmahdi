# Riad Oulmahdi

Data Scientist / ML Engineer — I build end-to-end ML projects, from notebook to deployed service. Currently completing a **Master's in Data Science** (Université de Caen Normandie), with a hybrid Data Science & ML Engineering profile.

**Currently looking for a 6-month final-year internship (stage de fin d'études), starting October 2026.**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

## What I do

- I build complete ML pipelines: data validation, feature engineering, training with experiment tracking, and production deployment via API.
- I'm particularly interested in LLM-based applications (RAG, semantic search) and classic machine learning applied to real business and research problems.
- I've worked on multimodal medical imaging (DICOM), sequential pattern mining on AIS ship-tracking data, and generative modeling (diffusion models).

## Projects

| Project | Description | Stack |
|---|---|---|
| [**Chatbot intelligent sur documents PDF**](https://github.com/RiadOulmahdi/Chat-with-pdfs) | RAG chatbot that answers natural-language questions over a knowledge base of PDFs. Full pipeline: OpenAI embeddings, ChromaDB vector store, GPT-4 generation, Streamlit UI. | LangChain, GPT-4, OpenAI Embeddings, ChromaDB, Streamlit |
| **IA pour prédire la toxicité d'une radiothérapie** | Comparative photon/proton study with the Centre François Baclesse on a 15-patient glioblastoma cohort. Multimodal integration of DICOM data (RTDose, RTStruct, CT, MRI) and 100+ clinical/cognitive variables; significant Pearson correlations between dose and structural atrophy. Compared deep learning (EfficientNet-B0) vs. classical models (Ridge, SVR) — R² = 0.80 for Ridge/SVR, with DL overfitting on the small medical cohort. | Python, DICOM, PyTorch, Scikit-learn |
| [**Pipeline MLOps — prédiction de prix immobilier**](https://github.com/RiadOulmahdi/Housing-price-prediction) | End-to-end MLOps pipeline for a real-estate price regression model. FastAPI serving with 4 endpoints, experiment tracking via MLflow (RMSE, MAE, mean error), interactive Streamlit dashboard, containerized with Docker. | MLflow, FastAPI, Docker, Streamlit, Scikit-learn |
| **Modèle de diffusion (DDPM) — Inpainting & Outpainting** | Conditional DDPM (UNet2DModel, 1000 timesteps) with masked loss and EMA stabilization. Trained on an RTX 3060 (150 epochs, Adam, FP16): 4h on CIFAR-10 (32×32), then 10h on Flower-102 (128×128) for sharper results. | PyTorch, Diffusers, Deep Learning |
| **Extraction de lignes maritimes régulières** | Partnership with Sinay to extract regular shipping lanes from AIS data covering 1,552 vessels. Frequent sequential pattern mining (GSP, PrefixSpan, CLoSPan) with sensitivity analysis on support threshold (1%–20%); identified high-support recurring routes (e.g. Marseille → Barcelona → Tangier, followed by 63 vessels). | Python, Pandas, Sequential pattern mining |

## Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![Diffusers](https://img.shields.io/badge/Diffusers-FFD21E?style=flat&logo=huggingface&logoColor=black)

**LLM & RAG**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-3B4252?style=flat)

**Data & Visualization**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)

**MLOps, Cloud & Tools**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GCP](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Anaconda](https://img.shields.io/badge/Anaconda-44A833?style=flat&logo=anaconda&logoColor=white)

**Serving & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

## Education

- **Master's in Data Science (M2)** — Université de Caen Normandie, 2024–2026
- **Bachelor's in Computer Science** — Université de Caen Normandie, 2022–2024

## Get in touch

I'm open to internship opportunities in Data Science / Machine Learning / MLOps starting October 2026 (6 months).

[LinkedIn](https://www.linkedin.com/in/riad-oulmahdi-322489239/)
[Email](mailto:oulmahdir@gmail.com)
