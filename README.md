# GraphEarlyWarnings

Personal project exploring risk signals through graphs and context.

## Overview

GraphEarlyWarnings is a self-directed project aimed at exploring early warning signals in stock markets through a holistic, graph-based approach. By combining risk intelligence from multiple domains—including credit, fraud, AML and ESG — with advanced entity resolution and network analysis, the goal is to build a non-correlated risk discrimination framework. Ultimately, the project aims to develop an AI-based agentic stock picker, where several specialized modules work together to identify attractive trading opportunities.

## Domain Expertise & Motivation

With 20 years experience in risk intelligence across various sectors, I believe that a holistic approach to risk assessment is crucial. This project reflects my passion for:
- **Risk Intelligence:** Leveraging diverse signals from credit, fraud, AML and ESG domains.
- **Graph Analytics:** Utilizing networks and graph features to uncover hidden relationships.
- **Agent-based Systems:** Experimenting with multiple agents working in tandem to produce actionable insights.
- **Self-directed Learning:** Advancing my Python skills and exploring the potential of advanced data analysis techniques.

## Market Focus

While the project is based in the US, it integrates insights from both the US and UK stock markets. The initial focus is on building robust modules for UK Companies House data extraction and analysis, with plans to expand to the US market and other data sources over time.

## Proposed Folder Structure

Below is the proposed folder structure for the project, designed to keep the work organized and scalable:

trading-agents/
├── README.md               # Overview, setup instructions, roadmap, etc.
├── requirements.txt        # Python dependencies
├── .gitignore              # Files to ignore in Git
├── docs/                   # Documentation and planning notes
├── uk/                     # UK-related data and code
│   ├── data/               # Raw and processed data from UK Companies House
│   ├── notebooks/          # Jupyter notebooks for UK data analysis
│   └── src/                # Python scripts for UK API calls, scoring, etc.
├── us/                     # (Future) US-related data and code
│   ├── data/
│   ├── notebooks/
│   └── src/
├── common/                 # Shared functions, utilities, or modules used across markets
│   └── helpers.py
