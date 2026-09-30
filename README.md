# AI-Powered Personal Knowledge Base

This repository contains a personal knowledge management (PKM) system integrated with a local AI model using Obsidian and Ollama.

## Setup Instructions
1. Run `docker-compose up -d` to start the local Ollama service and download the `llama3.2` model.
2. Open the `SecondBrain` folder as a vault in Obsidian.
3. The Smart Connections plugin is pre-configured to connect to the local model. Ensure it is enabled.

## Project Structure
- `SecondBrain/`: The Obsidian vault.
- `deliverables/`: Contains interaction logs and reflections.
- `docker-compose.yml`: Docker configuration for the local AI service.
