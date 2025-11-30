# 🛡️ Silent Guardian – Safety AI Agent 🤖  
### Capstone Project – 5 Day AI Agents Intensive Course  
**Track:** Enterprise Agents  

---

## ❗ Problem Statement
Organizations struggle to detect and respond to harassment across chats, emails, and collaboration tools — causing delayed action, legal risk, and employee harm.

## ✅ Solution
A **privacy-first multi-agent system** that scans communication streams, detects harassment patterns, generates safe intervention suggestions, builds evidence packets, and routes final decisions to human reviewers.

---

## 🔑 Key Features

- 🤖 **Multi-Agent System**: Ingestor, Extractor, Classifier, Pattern Detector, Risk Scorer, Planner, Evidence Builder, Ethics, Memory, Notifier  
- 🏢 **Enterprise Integrations**: Slack / Teams / Email / CSV (simulation-ready for real platforms)  
- 🛠️ **Custom Tools**: PII Redaction, Severity Scoring, PDF Evidence Generator, Moderator Action Stubs  
- 🧠 **Memory Bank**: User safety profiles & incident history (recidivism tracking)  
- 📊 **Observability**: Full pipeline logging, traces, and incident dashboards  
- 🔗 **Agent-to-Agent Communication (A2A)**: Structured pipeline + Message Bus  
- ⚖️ **Ethics & Human-in-the-Loop Controls**: High-risk actions require moderator/HR approval  
- 📄 **Evidence Generation**: Auto-generated Markdown/PDF evidence packets  

---

## 🧠 Key Concepts Demonstrated

### ✅ Multi-Agent System
- Multiple specialized agents working together  
- Centralized pipeline orchestrator  
- Sequential and event-driven execution  
- Real-time agent collaboration  

### ✅ Custom Tools & MCP (Model Control Plane)
- Simulated Google Search Tool  
- MCP-based switching between rule-based and LLM-sim classifier modes  
- Modular tool registry for safe upgrades  

### ✅ Sessions & Memory
- SQLite / In-Memory database for persistence  
- Incident history & recidivism tracking  
- Stateful context across executions  

### ✅ Observability
- End-to-end event logging  
- Tracks ingestion, classification, ethics checks, and escalations  
- Full auditability and debugging support  

### ✅ Agent-to-Agent Communication
- Pipeline-based orchestration  
- Message Bus (Pub/Sub) for async interactions  
- Agents acting as tools for other agents  

### ✅ Agent Evaluation
- Built-in Gold vs Predicted severity evaluation  
- Functional pipeline verification  
- Risk scoring validation  

---

## 🏗️ Architecture Highlights

- **Modular Design** – Each agent is independently replaceable  
- **Scalable** – Easy to add new models, tools, or platforms  
- **Observable** – Complete visibility into internal behavior  
- **Stateful** – Memory-driven intelligence  
- **Ethics-Aware** – Policy-gated automation  
- **Human-in-the-Loop Ready** – Built-in HR/Mediator escalation  

---

## 🎯 Value Proposition

This system enables organizations to:

- ✅ Detect harassment in real time  
- ✅ Prevent repeat abuse through behavior history  
- ✅ Reduce manual moderation workload  
- ✅ Maintain ethical compliance  
- ✅ Preserve legal evidence  
- ✅ Improve workplace trust & safety  

---

## 🚀 Future Enhancements

- Real Slack / MS Teams / Email API Integration  
- Sentiment trend analysis  
- Live Admin Dashboard  
- Role-Based Access Control (RBAC)  
- Multilingual detection  
- Web & Mobile Moderator Interface  

---

## ✅ Final Summary

**The Silent Guardian AI Safety Agent demonstrates how a multi-agent, memory-aware, observable, and ethics-driven AI system can be designed to automatically detect, assess, and intervene in harassment incidents at enterprise scale.**

