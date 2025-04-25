# MedicalDiagnosisAgent
This python script was adapted from the Google Developer Club. This notebook has an agentic model that makes diagnostics based on medical research on the web using Perplexity and Gemini API keys alongside a list of Lang graph tools. 

🧠 GDSC X BigTh!nk: AI Medical Diagnostics Agent
🩺 Project Overview
This project builds an AI-powered Medical Diagnostic Agent that simulates a preliminary consultation with a patient. The agent can:

Chat with users to understand their symptoms

Decide when enough information is collected to investigate possible conditions

Use external APIs (Gemini and Perplexity) to gather research

Analyze symptoms and research findings

Generate a structured report

⚠️ Disclaimer: This agent is for educational purposes only and is not a replacement for professional medical advice.

🌟 Key Concepts
LLMs as Orchestrators: The AI agent uses a large language model (LLM) to make decisions and control workflows.

LangChain + LangGraph: These libraries help manage AI workflows and tool usage with state transitions and memory.

Real-World Relevance: Mimics patterns used by professionals — collect data → conduct research → synthesize findings → generate reports.

🧰 Tools & Technologies

Tool/Library	Purpose
LangChain	Enables prompt orchestration and agents
LangGraph	Manages workflows and AI decision states
Gemini API	For large language model reasoning
Perplexity API	For retrieving relevant medical knowledge
Python + Colab	Execution and user interaction
