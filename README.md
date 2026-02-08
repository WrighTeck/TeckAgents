# 🤖 TeckAgents

**TeckAgents** is an AI agent development repository by **WrighTeck**, focused on designing, building, and documenting **goal-driven AI agents** for technology education and workflow automation.

Unlike traditional AI assistants that respond to individual prompts, TeckAgents explores **autonomous and semi-autonomous agents** that can plan tasks, execute multi-step workflows, use tools, maintain state, and evaluate outcomes.
![TeckAgents Overview](images/teckagents.jpg)
---

## 🎯 Project Goals

The goals of TeckAgents are to:

- Learn and apply modern **AI agent frameworks**
- Design **goal-oriented, workflow-based agents**
- Explore **multi-agent collaboration patterns**
- Build agents that **educate, guide, and execute**
- Document architectural decisions and lessons learned
- Create reusable foundations for future WrighTeck AI products

This repository serves as both a **learning lab** and a **technical portfolio**.

---

## 🧠 Agent Focus Areas

Agents developed in this repository will target practical education and execution in the following domains:

- **Coding & Software Development**
- **Software Testing & QA**
- **AI & Automation**
- **Tech Productivity**
- **Troubleshooting & Debugging**
- **Cybersecurity & Privacy** (defensive and educational)

Agents are designed to move beyond explanations and actively guide users through **real-world tasks and learning workflows**.

---

## 🧩 Agent Capabilities

Planned and in-progress agent capabilities include:

- Goal decomposition and task planning
- Multi-step execution and iteration
- Tool usage (code, files, APIs, documentation)
- State management and decision branching
- Role-based collaboration (instructor, reviewer, executor)
- Learning path generation and progress evaluation
- Structured outputs (lessons, checklists, test cases, reports)

---

## 🧰 Technologies, Frameworks & Tools

### Programming Language
- **Python** (primary language for agent logic and orchestration)

### Agent Frameworks
- **CrewAI** – role-based, task-oriented multi-agent systems  
- **LangGraph** – stateful, graph-based agent workflows  
- **AutoGen** – conversational and collaborative agent patterns  
- **MCP (Model Context Protocol)** – standardized tool and context integration  

### Supporting Tools & Concepts
- Async Python (`async` / `await`)
- Environment configuration (`.env`)
- File and data handling
- API integrations
- Logging and observability (as learning progresses)
- Prompt design and agent reasoning strategies

---

## 🧠 Models

This repository is **model-agnostic by design**.

Agents may be tested with different LLMs as supported by the frameworks used (e.g., OpenAI-compatible models, open-source models, or future integrations).

The focus is on **agent architecture, behavior, and orchestration**, not model lock-in.

---

## 📁 Repository Structure

```text
TeckAgents/
├── README.md
├── notes/
│   └── learning-notes.md
└── experiments/
