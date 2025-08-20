# Multi-agent System for Outlook Automation
We developed an AI agent for Outlook email automation using CrewAI and Ollama, with a crew of five agents and five tasks: categorizing, organizing, response generating, notifing and cleaning.

# Usage
## Clone repo
```
git clone https://github.com/silvermet999/email_auto_crewai/tree/master
```
## Graph API
You need to obtain admin access in order to use Graph API.
Follow the [link](https://developer.microsoft.com/en-us/graph/quick-start) to obtain the client ID. You also need tenant ID, obtained from [Azure](https://portal.azure.com/auth/login/)
## CrewAI installation
Follow [CrewAI](https://docs.crewai.com/en/installation) docs to install crewai
## Setup an .env file
It contains your LLM, Outlook credentials: ClientID and email

# References
- [CrewAI-Gmail-Automation](https://github.com/tonykipkemboi/crewai-gmail-automation)
- [CrewAI](https://github.com/crewAIInc/crewAI/)
- [Ollama](https://ollama.com/library)
- [GraphAPI](https://developer.microsoft.com/en-us/graph#get-started)
