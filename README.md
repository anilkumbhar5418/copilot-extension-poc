# GitHub Copilot Extension: Python AI Agent

This repository contains a custom Copilot Extension that integrates with a Python-based AI agent.

## Setup Instructions

1. Deploy the backend:
   ```bash
   pip install fastapi uvicorn
   uvicorn agent_backend:app --host 0.0.0.0 --port 8000
   ```

2. Update `copilot-agent-config.json`:
   - Replace `http://localhost:8000` with the deployed backend URL.

3. Install the GitHub App:
   - Go to [GitHub Apps](https://github.com/settings/apps) and create a new app.
   - Install the app on your repository or organization.

4. Use the Copilot Chat:
   - Install the Copilot Extension in your IDE.
   - Use the `process` command in Copilot Chat to interact with the AI agent.
