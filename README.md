# n8n-llm
- Integrates LLM utils into n8n.

## Setup
  - Create `.env` (see .env.example)
  - Run `docker-compose up -d`
  
### Ollama
  - Install on local: `brew install ollama`
  - Install Models: https://ollama.com/search
  - n8n: 
    - Setup Base URL: `http://host.docker.internal:11434`

### UI
  - n8n: http://localhost:5678/
  - open-webui: http://localhost:8080
  - Anything LLM: http://localhost:${SERVER_PORT}
