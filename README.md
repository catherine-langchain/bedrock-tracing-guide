# Tracing for AWS Bedrock

This project demonstrates how to instrument and trace `invoke_model` and `invoke_agent` calls in Amazon Bedrock to LangSmith, enabling you to monitor model & agent performance, latency, and token usage. 

---

# 🛠 Setup

1. Clone the repo

```shell
git clone https://github.com/catherine-langchain/bedrock-tracing-guide.git
cd bedrock-tracing-guide
```

2. Create and edit `.env` file in the root directory:
```shell
# Copy the .env.example file to .env
cp .env.example .env
```
