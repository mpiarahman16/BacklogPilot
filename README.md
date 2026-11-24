# BacklogPilot

**An AI copilot for Product Owners: from business request to sprint-ready AI backlog.**

Live demo: https://mpiarahman16.github.io/backlogpilot/

BacklogPilot shows how I turn a vague business request for an AI feature into work a team can start on Monday. You pick a request, and the agent walks through 7 steps to produce:

- **Epics and user stories** with acceptance criteria, story points, and priority (Must / Should)
- **AI success criteria:** evaluation metrics and targets, guardrails, human-in-the-loop rules, observability, and cost per request
- **A traceability matrix** linking each business requirement to its epics, stories, and how it will be verified
- **A sprint plan** that re-plans live when you change team velocity
- **A proof-of-concept plan** run as an experiment (hypothesis, scope, decision rule), plus an AI governance checklist
- **Export** to Markdown or a Jira-ready CSV

## The three sample requests

| Request | AI pattern |
|---|---|
| Smart address validation for shipping software | AI suggestions + tool calling to a carrier address API |
| Support answer assistant | Retrieval-augmented generation (RAG) with citations and handoff |
| Delivery exception agent | AI agent with tool calling, read-only tools, and human approval for claims |

## Why I built it

AI features fail in delivery, not in demos. The hard part of a Technical Product Owner's job is defining what "good" means for an AI capability: how it is evaluated, where a person stays in the loop, how it is monitored, and what it costs. Then you have to keep the backlog, the sprints, and the stakeholders aligned. BacklogPilot puts that whole workflow on one screen.

## Notes

- **Demo mode:** The agent's outputs are pre-written samples, so the demo runs anywhere at no cost. All targets are illustrative.
- **Next step:** Connect a live LLM with tool calling to generate backlogs from any request, with an evaluation set to score story quality.
- Single HTML file, no build step, no dependencies.

## About me

Pia Rahman, AI Product Manager. 10+ years in fintech, B2B SaaS, and regulated financial services. CSM, CSPO, SAFe Agilist.
GitHub: [mpiarahman16](https://github.com/mpiarahman16)
