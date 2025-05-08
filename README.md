# AI Personalization Service

## Overview
Ingest feature vectors via Spark, train a LightGBM model with MLflow tracking, and serve real-time personalization predictions on-prem with <4 ms latency, fully offline.

## Prerequisites
- Python 3.12
- Apache Spark 3.5
- On-prem GPU with CUDA drivers
- MLflow server (local or network-accessible)
- No internet egress (firewall rule)

## Installation
```bash
git clone <repo-url>
cd <repo>
python3.12 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
