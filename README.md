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

## Deploying to Netlify

This presentation is configured for easy deployment to Netlify:

1. Push this repository to GitHub
2. Log in to [Netlify](https://app.netlify.com/)
3. Click "New site from Git"
4. Select your GitHub repository
5. Use the following build settings:
   - Build command: `pip install -r netlify-requirements.txt && quarto render`
   - Publish directory: `_site`
6. Click "Deploy site"

The deployment configuration is already set up in the `netlify.toml` file.

## Project Structure

- `index.qmd`: Main presentation file
- `images/`: Contains presentation images
- `examples/`: LangGraph code examples

## Color Scheme

The presentation uses the CAS blue color (#00AEEF) for visual elements.

## Resources

- [LangGraph Documentation](https://langgraph.dev/)
- [Quarto reveal.js Documentation](https://quarto.org/docs/presentations/revealjs/)
- [Chainladder Package](https://chainladder-python.readthedocs.io/)

## Notes

[WSJ article - AI Agents Are a Moment of Truth for Tech](https://www.wsj.com/articles/ai-agents-are-a-moment-of-truth-for-tech-8ac5365a)

- Both workflows and agents
- Use LLMs to do stuff
- Workflows: LLMs follow predefined paths
- Agents: LLMs dynamically direct
