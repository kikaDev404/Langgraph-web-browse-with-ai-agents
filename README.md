# What This Project Does
This project provides an AI agent environment designed to assist users with web browsing through AI agents.  
It leverages **Microsoft Playwright** for automated browsing and information gathering.  
The collected results can then be sent to **Discord** using the **Discord Tool**.

# Key Functionalities
- Automate and retrieve information from any website by passing it to the LLM in chat.  
- Once satisfied with the results, you can push them directly to your Discord server if needed.  

# Discord Configuration
To enable Discord integration:
1. Configure a Discord bot for a server channel.  
2. Obtain the bot token.  
3. Add the token to the `.env` file.  

# Local vs Cloud LLM
By default, the project uses a locally hosted LLM via **Ollama**.  
If you prefer a cloud-based LLM, update the code with the corresponding API keys and endpoint.  

# Langsmith and Tracing
For tracing, generate an API key in **Langsmith** and provide it in the `.env` file.  

# Future Work
A feedback-driven LLM will be implemented to refine and improve the workflow in upcoming updates.  
