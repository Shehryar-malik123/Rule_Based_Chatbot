# Rule-Based Chatbot (Intelligent AI Student Assistant Engine)

## Overview
An engineering-grade, object-oriented (OOP) conversational engine developed in Python. This architecture shifts away from brittle, hardcoded conditional blocks by abstracting state routing rules into a decoupled data-logic engine. Designed using standard programmatic patterns, it natively manages text preprocessing normalization, state tracking vectors, and dynamic fallback exception gateways.

## Features
- **Object-Oriented Architecture (OOP):** Modular production design separating semantic database maps from runtime system logic.
- **Input Preprocessing & Sanitization:** Employs strict regular expression pipelines (`re`) to strip trailing whitespaces, enforce lowercase scaling, and purge punctuation noise.
- **Fuzzy Intent Optimization (Typo Heuristics):** Implements `difflib` sequence matching logic based on the Gestalt Pattern Matching paradigm to capture, score, and propose alternatives for user typos.
- **Dynamic Session Counters:** Monitors interaction threads and flags consecutive anomalies in real time.
- **Structural Fallback Gateways:** Employs automated execution blocks that halt operational loop fatigue after 3 consecutive unresolved parameters, gracefully routing users to system documentation.

## Technologies Used
- Python 3.x
- `re` (Regular Expression Engine)
- `difflib` (Sequence Heuristics Library)

## How to Run

Run the runtime architecture orchestrator clean via your terminal:
```bash
python chatbot.py
- help
- exit

## Author

Malik Shehryar
