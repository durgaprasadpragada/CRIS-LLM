# CRIS-LLM Dataset Repository
## Crypto Regulatory Insight System (CRIS-LLM): Supporting Dataset and Experimental Resources

This repository contains the datasets used in the research study:

CRIS-LLM (Crypto Regulatory Insight System): An LLM-Driven Computational Framework for Explainable Cryptocurrency Regulatory Risk Intelligence

The datasets support regulatory text analysis, semantic reasoning, severity scoring, and Regulatory Risk Intelligence Index (R2IF) construction.

---

# Repository Structure

CRIS-LLM-Dataset/

│

├── news/

│   ├── cryptonews.csv

│   ├── crypto_regulatory_news.csv

│

├── market/

│   ├── BTC.csv

│   ├── ETH.csv

│   ├── BNB.csv

│   ├── XRP.csv

│   ├── ADA.csv

│   ├── SOL.csv

│   └── other cryptocurrency price files

│

└── README.md


---

# Dataset Description

This repository contains two major categories of datasets:

---

# 1. Regulatory and Cryptocurrency News Dataset

Location:

news/

Files:

cryptonews.csv

crypto_regulatory_news.csv

These files contain:

• Cryptocurrency-related news articles  
• Regulatory announcements  
• Policy changes  
• Government regulations  
• Institutional statements  

Typical columns include:

Date

Title

Content

Source

URL

These datasets are used for:

• Regulatory intent classification  
• Policy severity estimation  
• Regulatory signal extraction  
• Semantic reasoning using LLM  

---

# 2. Cryptocurrency Market Dataset

Location:

market/

Files:

BTC.csv

ETH.csv

BNB.csv

XRP.csv

ADA.csv

SOL.csv

and other cryptocurrency price files.

Each file contains:

Date

Open

High

Low

Close

Volume

Market Cap

These datasets are used for:

• Market reaction analysis  
• Risk index validation  
• Regulatory impact assessment  
• Cross-asset comparison  

This enables correlation between regulatory risk and market behavior.

---

# Dataset Sources

These datasets were obtained from publicly available sources, including:

• Kaggle Cryptocurrency News Dataset

https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory

https://www.kaggle.com/datasets/oliviervha/crypto-news

https://www.kaggle.com/datasets/headsortails/crypto-news

• CoinMarketCap Historical Price Data

https://coinmarketcap.com/

• Public cryptocurrency regulatory news archives

• Cryptocurrency media platforms such as:

CoinDesk

CoinTelegraph

Bitcoin Magazine

CryptoSlate

---

# Purpose of Dataset in CRIS-LLM

These datasets are used to support the CRIS-LLM framework for:

• Regulatory event detection

• Regulatory severity scoring

• Regulatory Risk Intelligence Index (R2IF) construction

• Semantic reasoning and regulatory classification

• Temporal regulatory risk analysis

• Cryptocurrency market risk correlation

---

# Regulatory Risk Intelligence Index (R2IF)

CRIS-LLM processes regulatory news and computes:

Regulatory Severity Score

↓

Aggregates scores across time

↓

Constructs:

R2IF (Regulatory Risk Intelligence Index)

This index represents regulatory pressure in cryptocurrency markets.

Market data is used to validate the alignment between regulatory risk and price behavior.

---

# Data Characteristics

Dataset type:

Structured and semi-structured

Data format:

CSV

Time span:

2014 – 2023

Domain:

Cryptocurrency regulation and market data

No personal data is included.

No sensitive data is included.

All data is publicly available.

---

# Reproducibility

This dataset supports reproducibility of the CRIS-LLM framework, including:

Regulatory classification

Severity scoring

Risk index construction

Performance evaluation

Temporal analysis

---

# Citation

If you use this dataset, please cite:

CRIS-LLM (Crypto Regulatory Insight System):  
An LLM-Driven Computational Framework for Explainable Cryptocurrency Regulatory Risk Intelligence

---

# License

This dataset is provided for research and academic purposes only.

All original dataset rights belong to their respective public sources.

---

# Contact

For questions regarding this dataset or research:

Veerababu Reddy

Department of Computer Science and Engineering

Vignan's Foundation for Science, Technology & Research

India

Email:

rveerababu_vlits@vignan.ac.in

---

# End of README
