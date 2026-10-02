# AI IT Operations Agent

An Agentic AI-based IT Operations Agent built using Java, Spring Boot, Ollama, Llama 3.2, REST APIs, and Docker.

The system investigates IT incidents by dynamically selecting diagnostic tools, collecting observations, and using an LLM to determine the next investigation step.

---

## 🚀 Project Overview

Traditional IT operations troubleshooting often requires engineers to manually check:

- Application health
- CPU and memory usage
- Application logs
- Previous incidents
- Service response times

This project demonstrates an Agentic AI approach where an LLM acts as an IT Operations Agent.

The agent receives an incident and dynamically decides which diagnostic tool should be executed.

---

## 🧠 Agentic AI Workflow

```text
User Incident
      ↓
AgentController
      ↓
AgentOrchestrator
      ↓
Llama 3.2
      ↓
Select Diagnostic Tool
      ↓
Tool Execution
      ↓
Observation
      ↓
Llama 3.2
      ↓
Select Next Tool
      ↓
...
      ↓
Final Investigation
