# Langgraph-Multi-AI-Agent for Information Retrieval

This project implements a multi-agent conversational AI system using **LangGraph**, **LangChain**, **ChromaDB**, and **OpenAI's GPT-4o-mini**. The system is designed to handle queries about **insurance policies (Blue Cross Blue Shield - Federal Employee Program)**, **internet searches**, and **general small talk**.

## Features

- **Retriever Agent**: Uses a **vector store** (ChromaDB) to fetch relevant policy information.
- **Internet Search Agent**: Uses **DuckDuckGo Search** to retrieve real-time information.
- **Small Talk Agent**: Handles casual conversations.
- **Supervisor Agent**: Directs the query to the appropriate agent and ensures seamless execution.

## Usage

- Start the application and interact with the chatbot.
- Ask about **insurance policies**, **general facts**, or **casual conversation**.
- The system will **route** the request to the appropriate agent.

## Dependencies

- **LangChain**
- **LangGraph**
- **ChromaDB**
- **HuggingFace Embeddings**
- **DuckDuckGo Search**
- **OpenAI GPT-4o-mini**
- **Python 3.10+**

## Future Improvements

- Add **error handling** for rate limits in DuckDuckGo Search.
- Optimize **retrieval performance** with better indexing strategies.
- Implement **memory persistence** for ongoing conversations.
