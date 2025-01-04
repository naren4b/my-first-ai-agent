# This is my First Attempt to Creating an AI model

# Agent(phidata)

Agents are autonomous programs that achieve tasks using language models.
Engineers use phidata to build agents with memory, knowledge, tools and reasoning.

# Model(llama-3.3-70b-versatile)

Language Models are machine-learning programs that are trained to understand natural language and code. They provide reasoning and planning capabilities to Agents.

# Groq-Cloud(hosting the model)

With the seismic shift in AI toward deploying or running models – known as inference – developers and enterprises alike can experience instant intelligence with Groq. We provide fast AI inference in the cloud and in on-prem AI compute centers. We power the speed of iteration, fueling a new wave of innovation, productivity, and discovery. Groq was founded in 2016 to build technology to advance AI because we saw this moment coming.

# Tools(YahooFinance/DuckDuckGo etc)

Tools are functions that an Agent can run like searching the web, running SQL, sending an email or calling APIs. Use tools integrate Agents with external systems.

# Setup

1. Register at https://console.groq.com/
2. Create an Access Key : https://console.groq.com/keys

Install needed libraries

```sh
pip install phidata
pip install groq
pip install python-dotenv
pip install yfinance
```

ENV values inject the Access key in a file like this

```sh
GROQ_API_KEY=gsk_xxx
OPENAI_API_KEY=openai_xxx

```

# Run
```sh

python my_fin_ai_agent.py  

```
![ai response](ai_response.png)
