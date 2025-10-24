# 1️⃣ Clone the repo
git clone https://github.com/your-username/CYBERPROJECT.git
cd CYBERPROJECT

# 2️⃣ Create a virtual environment
python3 -m venv .venv

# 3️⃣ Activate it
source .venv/bin/activate

# 4️⃣ Upgrade pip
python -m pip install --upgrade pip

# 5️⃣ Install dependencies
python -m pip install -r requirements.txt

Verfication of installation 
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
python - <<'PY'
import fastapi, pathway, sklearn, pandas, numpy, requests
print("✅ All dependencies loaded successfully!")
print("FastAPI:", fastapi.__version__)
print("Pathway:", pathway.__version__)
PY


CYBERPROJECT/
├── data/               # datasets and ETL inputs
├── generators/         # data generators, enrichment, ETL pipeline
├── service/           # FastAPI backend
├── requirements.txt    # dependency list
├── SETUP.md            # setup instructions (this file)
└── README.md           # project overview

to update dependecies 
pip install -r requirements.txt --upgrade


for windows 
# 🧠 CyberProject — Local Setup Guide

Welcome! 👋  
This document explains how to **set up and run CyberProject** on your system (Windows, macOS, or Linux/WSL).

---

## 📦 Requirements

- **Python 3.10+** (recommended: 3.12)
- **Git**
