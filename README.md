## Overview

This is Chain Concierge, a bot that summarizes all of your proposal requests for each protocol.

This uses Langchain.

---

## To run

Make sure to fill in the API keys for OpenAI and install all the dependencies. If not working, check the error log on streamlit site, they will let you know which ones you have to install.

```
python -m venv venv
source venv/bin/activate
pip install openai langchain
pip install openai chromadb
pip install bs4
pip install python-dotenv
pip install tiktoken
pip install streamlit
```
