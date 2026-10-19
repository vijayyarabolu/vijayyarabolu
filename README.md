## Hi, I'm Vijay

I'm an AI engineer. I build LLM agents, RAG systems and the evals that keep them honest, mostly in Python on Claude, Amazon Bedrock and LangGraph.

At work I've shipped a Claude invoice-coding agent used across 30+ communities, a hybrid-search RAG assistant over 1,100 internal manuals, and Bedrock agents with MCP tooling for a financial reconciliation team. That code is private, so the repos here are things I built on my own time.

### Projects

| Repo | What it is |
|---|---|
| [job-hunt-agent](https://github.com/vijayyarabolu/job-hunt-agent) | Pulls fresh roles straight from company ATS boards, ranks them against your profile and tracks applications. I use it for my own search. |
| [resume-tailor](https://github.com/vijayyarabolu/resume-tailor) | Tailors a resume to a job description with Claude, but only rewrites facts that exist in your fact bank, and checks ATS keyword coverage. |
| [maxie-assistant](https://github.com/vijayyarabolu/maxie-assistant) | A voice assistant with a cost-aware router (most commands never call an LLM), a monthly budget cap and confirmations for risky actions. |
| [support-context-assistant](https://github.com/vijayyarabolu/support-context-assistant) | Multi-tenant support agent on Bedrock AgentCore. Tenant isolation enforced in the tools, with an eval that counts cross-tenant leaks. |
| [insurance-underwriting-agent](https://github.com/vijayyarabolu/insurance-underwriting-agent) | Underwriting decision support where deterministic rules decide and the LLM only explains. A 38-case eval tracks unsafe auto-approvals. |

Each repo runs offline in a demo mode, has tests and CI, and its README says what was measured and what wasn't.

### Stack

Python, Claude API, Amazon Bedrock and AgentCore, LangGraph, MCP, hybrid search and reranking, LoRA fine-tuning, LangSmith and OpenTelemetry, AWS, Docker, Kubernetes.

### Contact

[LinkedIn](https://www.linkedin.com/in/vijay-yarabolu/)
