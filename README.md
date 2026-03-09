# When Metrics Fail  
## Why Institutional Food Waste Logs Don’t Enable Accountability

### Intro
50 — but 50 what? Pounds? Pans? Portions? This question, unanswerable from real institutional food waste logs, is the starting point for this project.

### Overview
This project examines a real-world food usage log used in a large institutional kitchen and evaluates whether the log can meaningfully measure food waste or support accountability.

Rather than analyzing numerical outputs, this project focuses on **measurement validity** — specifically, whether the data collection system itself is capable of answering the questions it claims to inform.

### Motivation
While reviewing food waste documentation from an institutional kitchen, I noticed that the recorded values lacked defined units, consistent context, and a clear relationship to production or demand. This raised a critical question:

> *Can this measurement system actually support decisions about food waste reduction?*

This project was created to explore that question analytically and systematically.

### Core Question
**Is the current food usage log capable of measuring food waste in a way that supports accountability and decision-making?**

### Project Scope
This analysis does **not** attempt to quantify actual food waste amounts.

Instead, it:
- Evaluates the structure of the measurement system
- Identifies missing requirements for meaningful metrics
- Demonstrates why the recorded values cannot support comparison, trend analysis, or accountability
- Proposes minimal changes that would make the log actionable

### Artifact
The primary artifact analyzed in this project is a food usage log used to record:
- Menu items
- Starting quantities
- Additions
- Remaining quantities
- Census counts

A de-identified example of this log is included in the `artifact/` directory.

### Key Findings
- The unit of measurement (“servings”) is undefined and inconsistent
- Recorded values cannot be meaningfully compared or aggregated
- The log cannot support trend analysis or waste reduction decisions
- The system prioritizes documentation over actionable insight

### Structure
- `artifact/` – Example of the food usage log
- `analysis/` – Measurement requirements and evaluation
- `proposal/` – Minimal metric redesign suggestions
- `assumptions_and_limitations.md` – Explicit scope boundaries
- `reflections.md` – Broader implications for accountability and metrics

### Tools Used
This project prioritizes analytical reasoning over technical execution. The failure identified exists at the system design level, before any data analysis tool could help.

---

### Author
Steven Cockrum
