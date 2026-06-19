# Multi-Agent Exploratory Data Analysis (EDA) System using AutoGen

## Overview

Exploratory Data Analysis (EDA) is a critical step in the data science lifecycle. It involves understanding data structure, identifying patterns, detecting anomalies, generating statistical summaries, and creating visualizations before building predictive models.

This project implements an AI-powered Multi-Agent EDA Framework using AutoGen, where multiple specialized agents collaborate to automate the EDA workflow. Each agent performs a dedicated role and communicates with other agents to produce a comprehensive, high-quality EDA report.

---

## Problem Statement

Traditional EDA workflows often involve:

* Data cleaning and preprocessing
* Statistical analysis
* Data visualization
* Insight generation
* Report preparation
* Review and validation

Managing these tasks manually can be time-consuming and prone to inconsistencies. This project addresses these challenges through a collaborative multi-agent architecture.

---

## Solution Architecture

The system consists of multiple AI agents working together:

### Data Preparation Agent

* Cleans and preprocesses raw data
* Handles missing values
* Ensures dataset readiness for analysis

### EDA Agent

* Performs statistical analysis
* Generates descriptive summaries
* Identifies patterns and trends
* Creates visual insights

### Report Generator Agent

* Compiles findings into a structured report
* Summarizes key insights
* Documents visualizations and conclusions

### Critic Agent

* Reviews generated outputs
* Provides feedback for improvement
* Ensures clarity, completeness, and quality

### Executor Agent

* Executes and validates generated code
* Verifies outputs and results
* Ensures analytical correctness

### Admin Agent

* Oversees the workflow
* Coordinates agent interactions
* Ensures project objectives are met

---

## Workflow

1. Dataset is provided to the system.
2. Data Preparation Agent cleans and prepares data.
3. EDA Agent performs exploratory analysis.
4. Report Generator creates an initial report.
5. Critic Agent reviews and suggests improvements.
6. Executor validates analysis and code outputs.
7. Final report is generated and approved by Admin.

---

## Features

* Multi-agent collaboration using AutoGen
* Automated data preparation
* Exploratory data analysis
* Statistical summaries
* Insight generation
* Report generation
* Feedback-driven refinement
* Modular and extensible architecture

---

## Technology Stack

* Python
* AutoGen
* Google Colab
* OpenAI / LLM-based Agents
* Jupyter Notebook

---

## Project Structure

```text
├── 6_C13_M3_L10_Project_AutoGen.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Business Value

This framework:

* Reduces manual effort in EDA
* Improves consistency and reproducibility
* Enables scalable analytical workflows
* Produces higher-quality insights through agent collaboration
* Demonstrates practical application of Generative AI and Multi-Agent Systems

---

## Key Learning Outcomes

* Multi-Agent System Design
* Agent Collaboration and Coordination
* Automated Data Analysis Workflows
* Prompt Engineering for Agentic AI
* Report Generation using AI Agents
* Human-in-the-Loop Review Processes
* AutoGen Framework Implementation

---

## Author

### Antony Pradeep Raj

**ERP Product Manager | Aspiring AI Product Manager**

With nearly 20 years of experience in ERP Product Management, Business Process Automation, and Digital Transformation, I am currently expanding my expertise into Generative AI, Retrieval-Augmented Generation (RAG), AI Agents, and AI Product Management.

GitHub: https://github.com/antonypradeep54

---

## License

This project is licensed under the MIT License.
