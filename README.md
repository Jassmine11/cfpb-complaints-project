# cfpb-complaints-project
### Data

The CSV dataset is too large for GitHub.  
Download it here: [(https://drive.google.com/file/d/18Z8BzgekGwjwjBnTTGUC3znMfJ2BSUmj/view?usp=sharing)]

Capstone Project: GenAI-Powered Customer Intelligence System

Project Overview

Banks and financial institutions receive massive volumes of unstructured customer feedback from app reviews, support tickets, surveys, and more. 
Manual analysis is slow, decentralized, and prone to compliance risks.

Goal: Build an end-to-end system that ingests, analyzes, and summarizes customer feedback while maintaining compliance and traceability. 
Key modules include:
	•	NLP for sentiment classification, topic extraction, and risk detection
	•	Customer segmentation via clustering
	•	Generative AI (LLMs) for executive summaries, escalation drafts, and role-specific insights
	•	Compliance-aware layer for PII redaction, hallucination detection, and audit logging
	•	Dashboard visualization (Streamlit or Power BI)
	•	Optional AI agent/chatbot for on-demand insights

⸻

Data Collection

Source 1: CFPB Consumer Complaints
	•	Description: Consumer complaints submitted to the CFPB, covering a variety of banking and financial products.
	•	Data Type: Structured CSV
	•	Size: 6.45GB (10,425,605 total complaints)
	•	Relevance: Ideal for NLP tasks, sentiment analysis, topic extraction, risk detection, and customer segmentation.
	•	Download Link: [(https://drive.google.com/file/d/18Z8BzgekGwjwjBnTTGUC3znMfJ2BSUmj/view?usp=sharing)] – CFPB Dataset
	•	Collection Method: Bulk download from CFPB portal: CFPB Data// https://www.consumerfinance.gov/data-research/consumer-complaints/search/?dateRange=All&date_received_max=2025-08-13&date_received_min=2011-12-01&page=1&searchField=all&size=25&sort=created_date_desc&tab=List


⸻

Data Handling & Compliance
	•	PII Redaction: Personally identifiable information removed using spaCy and regex.
	•	Audit Logging: Logs kept for all data processing and AI prompts/responses to ensure traceability and compliance.
 
