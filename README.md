# What this project does
This is a AI agent environment which aims to help users with Web browsing using AI agents. This project use Microsoft Playwright for web browsing and info gathering automation. The result of the browsing can then be send to **Discord** using **Discord Tool**. 

# Key Functionalities
You can retrive and autoamte the info gathering from any website which is passed to the llm in the chat. 
once you are happy with the results, you can then push the results to the discord server if needed.

# Discord config
If you want to push the info to discord, you need to config a discord bot to a server's channel and get the discord bot token. Once you have done these, mention the token in the env file. 

# Local vs Cloud LLM
Currently, the project use locally ran llm using **Ollama**. if you want to use a cloud based LLM, config the same in the code. Change the end point and the keys in the code accordingly. 

# Langsmith and tracing
if you want tracing, make an API key in Langsmith and provide the same in env file.

# For future work
A feedback LLM is neede to polish the work flow and will be implemented in the coming days