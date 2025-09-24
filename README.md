# CEO-Agent

## Overview
The CEO Agent is the central orchestrator of the NetcoRobo AI ecosystem.
It is built using Ango framework in Python, with MCP integration for multi-agent communication.

The agent is designed with:
  - Reasoning: Strategic decision-making and planning
  - Memory: Session + persistent memory via SQLite
  - Knowledge Base: Company mission, values, governance rules
  - Scalable Architecture: Foundation for cloning into CTO, CFO, HR and other specialized agents.

## Tech Stack
  - Language: Python 3.10+
  - Framework: Agno AI
  - LLM Models: OpenAI GPT-4o / GPT-5 (via API key)
  - Memory: SQLite (long-term storage of conversations)
  - Protocol: MCP (Model Context Protocol)

## Setup Instructions

1. Clone the Repository
```bash
git clone https://github.com/happybigocean/ceo-agent.git
cd ceo-agent
```

2. Create Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Set Up Environment Variables
Create a .env file in the project root:
```ini
OPENAI_API_KEY=your_openai_key_here
```

5. Run the CEO Agent
```bash
python main.py
```

