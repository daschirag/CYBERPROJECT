# 🛡️ CyberShield — AI-Powered Cybersecurity Intelligence Platform

> **Next-Gen AI-driven cybersecurity suite** for detecting phishing, intrusion, anomalies, and real-time network threats using FastAPI, Pathway, and ML.

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-success?logo=fastapi)
![Pathway](https://img.shields.io/badge/ETL-Pathway-orange)
![MachineLearning](https://img.shields.io/badge/AI-Scikit--learn%20%7C%20PyTorch-green)
![Status](https://img.shields.io/badge/Build-Passing-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 🔍 Overview

**CyberShield** is an **AI-Powered Cybersecurity Intelligence System** that brings together 8 core modules — simulating how a modern SOC (Security Operations Center) functions using automation and AI.

The platform uses **Pathway ETL** for streaming data, **FastAPI** for backend services, and **Machine Learning** for anomaly & phishing detection.

It’s designed as a learning + deployable platform for **students, researchers, and security startups**.

---

## ⚙️ Tech Stack

| Layer | Technology |
|--------|-------------|
| **Programming** | Python 3.12 |
| **Backend API** | FastAPI + Uvicorn |
| **ETL / Streaming** | Pathway |
| **AI & ML** | Scikit-Learn, PyTorch, Pandas |
| **Security Tools** | VirusTotal API, AbuseIPDB, Shodan (future) |
| **Visualization** | Streamlit / React dashboard |
| **Deployment** | Docker / Render / Railway |
| **GPU Support** | CUDA-enabled PyTorch |

---

## 🧠 Core Modules (8 Features)

| # | Module | Description |
|:-:|:--------|:-------------|
| **1** | 📨 **Phishing & Email Threat Detector** | Analyzes email text, links, and domains for malicious indicators using AI scoring. |
| **2** | 🌐 **URL & Domain Reputation Analyzer** | Checks URLs/domains against blacklists, suspicious TLDs, and VirusTotal API results. |
| **3** | 🔍 **Path Traversal & Vulnerability Lab** | Simulates web app attacks (e.g., directory traversal) for security awareness. |
| **4** | 📊 **Network Log & Packet Analyzer** | Uses ETL (Pathway) to ingest and process system/network logs for anomalies. |
| **5** | 🧬 **AI-Driven Anomaly Detection Engine** | Detects abnormal user or system behavior using unsupervised ML models. |
| **6** | 🧩 **ETL Pipeline Automation** | Real-time log and event data pipeline using Pathway — continuous monitoring. |
| **7** | 🔒 **Threat Intelligence Hub** | Aggregates open-source feeds (PhishTank, AbuseIPDB, Shodan) into actionable alerts. |
| **8** | 📈 **Visualization Dashboard** | Real-time dashboard for security alerts, logs, and trends (using Streamlit/React). |

CYBERPROJECT/
├── data/ # datasets, logs, ETL inputs
├── generators/ # synthetic data generators (emails, URLs, logs)
│ ├── email_generator.py
│ └── enrich_urls.py
├── service/ # FastAPI backend (detection + alerts)
│ ├── main.py
│ └── anomaly_model.py
├── models/ # trained ML models
│ └── phishing_model.joblib
├── notebooks/ # ML experiments and research
├── requirements.txt
├── SETUP.md
└── README.md

+---------------------+
| Synthetic Generator| ---> sends simulated data streams
+---------------------+
|
v
+---------------------+
| Pathway ETL Engine | ---> cleans, enriches, and routes data
+---------------------+
|
v
+---------------------+
| FastAPI Detection | ---> applies rules, ML, and scoring
| Service |
+---------------------+
|
v
+---------------------+
| Alerts API / DB | ---> stores alerts and serves UI
+---------------------+
|
v
+---------------------+
| Streamlit Dashboard | ---> real-time visualization
+---------------------+



---

## 🧱 Project Architecture

