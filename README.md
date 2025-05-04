# AI-Empowered Actuaries: An Introduction to AI Agents

Presentation for the Casualty Actuarial Society (CAS) Spring 2025 Meeting.

## Project Overview

This presentation introduces AI agents to actuaries, focusing on their practical applications in actuarial work. It covers:

- What sets agents apart from standard LLMs
- How agents can plan, reason, and take action
- Examples of actuarial agents built using LangGraph
- Code samples for experimentation

## Setup Instructions

### 1. Install Quarto

This presentation uses Quarto with reveal.js. Install Quarto from: https://quarto.org/docs/get-started/

```bash
# macOS (using Homebrew)
brew install quarto

# Verify installation
quarto check
```

### 2. Python Environment Setup

```bash
# Create a virtual environment
python -m venv venv

# Activate the virtual environment
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### 3. Run the Presentation Locally

```bash
quarto preview
```

## Project Structure

- `index.qmd`: Main presentation file
- `images/`: Contains presentation images

## Resources

- [LangGraph Documentation](https://langgraph.dev/)
- [Quarto reveal.js Documentation](https://quarto.org/docs/presentations/revealjs/)
- [Chainladder Package](https://chainladder-python.readthedocs.io/)

## Notes

[WSJ article - AI Agents Are a Moment of Truth for Tech](https://www.wsj.com/articles/ai-agents-are-a-moment-of-truth-for-tech-8ac5365a)
