# LangSmith QuickStart

## Introduction

**LangSmith** is a platform for building production-grade LLM applications. It allows you to closely monitor and evaluate your application, so you can ship quickly and with confidence. Use of LangChain is not necessary - LangSmith works on its own! 

### Install LangSmith

```python
pip install -U langsmith
```

### Create an API key

To create an API key head to the Settings page. Then click Create API Key.

### Setup your environment

```python
export LANGCHAIN_TRACING_V2=true
export LANGCHAIN_API_KEY=<your-api-key>

# The below examples use the OpenAI API, though it's not necessary in general
export OPENAI_API_KEY=<your-openai-api-key>
```