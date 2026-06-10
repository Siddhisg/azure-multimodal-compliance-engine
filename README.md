# Azure Multimodal Compliance QA Pipeline

## Overview

The Azure Multimodal Compliance QA Pipeline is an end-to-end LLMOps solution designed to automate compliance validation for marketing and influencer video content. The system leverages Azure AI services, Retrieval-Augmented Generation (RAG), LangGraph orchestration, and observability tools to analyze content, identify policy violations, and generate structured compliance reports.

This project demonstrates the implementation of a production-oriented multimodal AI workflow capable of processing video content, retrieving relevant compliance guidelines, evaluating content against regulatory requirements, and providing actionable compliance insights.

---

## Business Problem

Organizations and brands must ensure that marketing campaigns, influencer content, and promotional videos comply with advertising regulations, platform policies, and internal brand guidelines.

Manual compliance review is often:

* Time-consuming
* Resource-intensive
* Difficult to scale
* Susceptible to human error

This solution automates the review process by combining multimodal AI capabilities with intelligent retrieval and agent-based reasoning.

---

## Key Features

* Automated compliance validation for video content
* Retrieval-Augmented Generation (RAG) architecture
* LangGraph-based workflow orchestration
* Compliance rule retrieval using Azure AI Search
* Policy violation detection and explanation
* Structured compliance report generation
* End-to-end tracing using LangSmith
* Application monitoring through Azure Application Insights
* Scalable cloud-native architecture

---

## Solution Architecture

The system follows a multi-stage workflow:

1. Video content ingestion
2. Content and transcript extraction
3. Compliance guideline retrieval
4. Agentic reasoning and evaluation
5. Violation detection
6. Report generation
7. Monitoring and observability

### Architecture Diagram

![Architecture](docs/architecture.png)

---

## Technology Stack

### Cloud Services

* Microsoft Azure
* Azure OpenAI
* Azure AI Search
* Azure Application Insights

### AI & LLMOps

* LangGraph
* LangChain
* LangSmith
* GPT Models
* Retrieval-Augmented Generation (RAG)

### Development

* Python
* UV Package Manager

---

## Workflow

### Step 1: Content Ingestion

Video content is provided as input for compliance evaluation.

### Step 2: Compliance Knowledge Retrieval

Relevant compliance rules and advertising policies are retrieved using Azure AI Search.

### Step 3: Agentic Evaluation

LangGraph orchestrates multiple reasoning steps to evaluate the content against compliance requirements.

### Step 4: Violation Detection

The system identifies potential compliance issues and generates supporting explanations.

### Step 5: Compliance Report Generation

A structured report is produced containing:

* Compliance status
* Identified violations
* Supporting evidence
* Recommendations

### Step 6: Monitoring and Observability

All workflow executions are traced and monitored using LangSmith and Azure Application Insights.

---

## Project Structure

```text
ComplianceQAPipeline/
│
├── main.py
├── pyproject.toml
├── uv.lock
├── README.md
├── .env.example
├── .gitignore
│
├── docs/
│   ├── architecture.png
│   └── screenshots/
│
└── sample_data/
```

---

## Screenshots

### LangGraph Workflow

Add screenshot here.

### LangSmith Execution Trace

Add screenshot here.

### Azure Application Insights Dashboard

Add screenshot here.

### Compliance Report Output

Add screenshot here.

---



### Install Dependencies

Using UV:

```bash
uv sync
```

Or using pip:

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

Create a `.env` file based on `.env.example`.

Example:

```env
AZURE_OPENAI_ENDPOINT=
AZURE_OPENAI_KEY=

AZURE_SEARCH_ENDPOINT=
AZURE_SEARCH_KEY=

LANGSMITH_API_KEY=

APPLICATIONINSIGHTS_CONNECTION_STRING=
```

### Run the Application

```bash
python main.py
```

---

## Observability

### LangSmith

* Workflow tracing
* Agent execution monitoring
* Prompt debugging
* Run analysis

### Azure Application Insights

* Application monitoring
* Performance metrics
* Error tracking
* Operational visibility

---

## Sample Use Cases

* Influencer marketing compliance review
* Advertising policy validation
* Brand governance automation
* Marketing campaign approval workflows
* Regulatory compliance assessment

---

## Future Enhancements

* Real-time compliance validation
* Multi-language support
* Interactive compliance dashboard
* Human-in-the-loop review process
* Automated remediation recommendations

---

## Skills Demonstrated

* LLMOps
* Agentic AI Workflows
* Retrieval-Augmented Generation (RAG)
* Azure OpenAI
* Azure AI Search
* LangGraph
* LangSmith
* Application Monitoring
* Cloud-Based AI Solutions
* Prompt Engineering
* Python Development

---

## Author

Siddhi Gaikwad

