## Overview

Keep track of all the governance proposals that come up on DAOs with our Chain Reporter, which summarizes the key points of the proposals in an instant. You can publish this as a newsletter by linking it to your Gmail account, Slack, or Discord.

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
streamlit run chatbot.py
```
