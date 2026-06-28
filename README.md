# About Me
**Location:** Zürich, Switzerland  
**LinkedIn:** https://www.linkedin.com/in/carloderossi

I design production AI architectures that pass regulatory scrutiny — FINMA, SR 11-7, EU AI Act — in financial institutions, under regulation, at scale.

Currently working in Switzerland in a Swiss Financial institution, leading AI-enabled transformation of enterprise portfolios. I architected a GNN/ML clustering model analyzing **20K+ application dependencies**, delivering **CHF 50M+** in technical debt reduction.

Beyond my day job, I explore cutting-edge AI architectures through **10+ production‑grade systems**.

---

## What I Do

- AI Architecture for regulated environments (FINMA · SR 11-7 · EU AI Act)  
- Agentic systems & multi-agent orchestration (LangGraph · MCP · A2A)  
- RAG systems & LLM deployment on Azure AI Foundry  
- Model risk governance & MLOps/AIOps in financial services  
- End-to-end AI product delivery: from architecture to production 
- Financial ML (anomaly detection, recommendations, forecasting)  
- AI infrastructure (custom MCP servers, agent protocols)  

---

# Featured Projects

## Agentic Systems & Orchestration

### **Self-Healing ML Agentic Demo**
Agentic MLOps loop that detects data drift, reasons about it via LLM agents, and autonomously retrains — including synthetic data acquisition when retraining alone is insufficient.  
Agents operate with memory and historical context to avoid repeated mistakes. Orchestrated with LangGraph for modular, inspectable workflows.  
**Tags:** LangGraph · Agentic MLOps · Drift Detection · Self-Healing · Synthetic Data

### **Multi-Agent Collaboration using MCP Registry and A2A Protocol Implementation**
Multi-agent communication system with dynamic agent discovery via MCP resources and AgentCards.  
Enables autonomous agent coordination without hardcoded dependencies.  
This example demonstrates how a dynamic MCP Agent Registry can be combined with the Agent-to-Agent (A2A) protocol to build discoverable multi-agent systems.
The MCP Registry acts as a centralized discovery service, while A2A provides the communication protocol between agents.
MCP Registry → Agent Discovery A2A Protocol → Agent Communication
**Tags:** LangChain · MCP · Multi-Agent · A2A Protocol

### **Custom MCP Server**
Custom Model Context Protocol server for career assistance.  
Demonstrates systems-level understanding of emerging AI infrastructure.  
**Tags:** MCP · Claude · Python

### **Agentic RAG System**
RAG system with autonomous reasoning capabilities using DeepSeek for cost‑optimized GenAI deployment.  
**Tags:** RAG · DeepSeek · LangChain · Autonomous Agents

### **Multi-Agent RL Auction**
Competing agents with different RL policies simulating bidding strategies.  
Demonstrates multi-agent coordination and game theory.  
**Tags:** Reinforcement Learning · Multi-Agent · Game Theory

### **MCP Agents Registry**
AI Agents can be registered and deregistered dynamically via MCP tools.
AgentCards are persisted in a JSON registry.
Each AgentCard is exposed as an MCP Resource.
Resources use an A2A-style URI scheme (`agent://<agent-name>`).
Clients can discover available agents through MCP resource listing and retrieve individual AgentCards.
**Tags:** MCP · A2A · AI AGents · FastMCP


---

## MLOps & Infrastructure

### **Production MLOps Pipeline**
End-to-end MLOps ecosystem using MLflow, GitHub Actions, and Evidently AI — from training script to governed, schema-enforced production API.  
Features model signatures, zero-downtime Blue/Green deployment via Docker healthchecks, staging/production environment isolation, and drift detection dashboards.  
**Tags:** MLflow · GitHub Actions · Evidently AI · Docker · Model Registry · Monitoring

### **Production MLOps Champion/Challenger demo**
This repository demonstrates a complete Champion-Challenger framework for safe model deployment in production Machine Learning, with a focus on regulated environments such as credit risk modeling.
Built on Azure Machine Learning, it showcases shadow deployment, Population Stability Index (PSI) drift detection, automated monitoring, and a governed promotion process to replace models without risking production decisions.
Explore how to run challenger models in parallel with the live champion, compare their performance on real traffic, and implement robust safeguards against model degradation and concept drift.
Ideal for MLOps practitioners, quantitative risk teams, and anyone implementing IFRS 9-compliant or similarly regulated ML systems.
The project includes end-to-end pipelines, monitoring configurations, and practical examples drawn from real-world production challenges in financial services.

---

## Financial ML Applications

### **Credit Card Fraud Detection**
Anomaly detection for financial transactions.  
Applicable to wealth management compliance monitoring and unusual transaction detection.  
**Tags:** Anomaly Detection · Financial Services · Classification

### **Time Series Forecasting**
Neural forecasting models with Optuna hyperparameter optimization. Production version running on Azure and PySpark (Optuna optimization, Distributed ML)
Applicable to portfolio return prediction and market trend analysis.  
**Tags:** Time Series · Optuna · Neural Networks · Forecasting

---

## ML Foundations & Visualization

### **ML Animations**
Interactive visualizations of bias–variance trade-off and gradient descent with momentum.  
Useful for explaining complex ML concepts to non-technical stakeholders.  
**Tags:** Education · Visualization · ML Theory

### **Dimensionality Reduction**
Mushroom dataset analysis using PCA, t‑SNE, and UMAP.  
**Tags:** PCA · t‑SNE · UMAP · Feature Engineering

### **GANs Implementation**
Generative Adversarial Networks for image generation.  
**Tags:** GANs · Deep Learning · Generative AI

---

## LLM Fine-Tuning & Research

### **Detective Fiction Fine-Tuning Lab**
Production-ready toolkit for fine-tuning LLMs on classic detective fiction (Sherlock Holmes & Hercule Poirot) using Unsloth.  
Covers full pipeline: dataset preparation with quality analysis, LoRA SFT on Qwen 2.5, PPO-based reinforcement learning, LLM-as-judge evaluation, and embedding-based style drift analysis (cosine similarity: 0.73).  
**Tags:** Unsloth · LoRA · Fine-Tuning · Qwen · PPO · RL · LLM-as-Judge


# 📫 Let's Connect

IT <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/it.svg" width="32"/>  
EN <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/gb.svg" width="32"/> <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/us.svg" width="32"/>  
DE <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/ch.svg" width="32"/> <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/de.svg" width="32"/>  
PT <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/br.svg" width="32"/> <img src="https://cdn.jsdelivr.net/gh/lipis/flag-icons/flags/4x3/pt.svg" width="32"/>  



⭐️ *If you find my work interesting, consider starring some repos!*
