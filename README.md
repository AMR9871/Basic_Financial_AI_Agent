# AI Financial Agent with Phi Framework

A powerful multi-agent system that combines web search capabilities with financial analysis tools, built using the Phi framework.

## Overview

This repository contains a sophisticated AI assistant system that:
1. Analyzes financial data from YFinance
2. Searches the web for relevant information
3. Combines these capabilities to provide comprehensive financial insights
4. Includes a user-friendly Playground interface

## Features

- **Multi-Agent Architecture**: Combines specialized agents for different tasks
- **Financial Analysis**: Stock prices, analyst recommendations, fundamentals, and company news
- **Web Search Integration**: Uses Google Search and DuckDuckGo to find latest information
- **Interactive Playground**: Test and experiment with the agents through a web interface
- **Powered by LLaMA 3**: Leverages Groq's LLaMA 3 70B model for high-quality responses

## Repository Structure

- `financial_agent.py`: Main implementation of the financial agent system
- `playground.py`: Interactive playground interface for testing the agents

## Requirements

- Python 3.8+
- Phi Framework
- OpenAI API key
- Phi API key
- Groq API key

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/financial-ai-agent.git
cd financial-ai-agent

# Install dependencies
pip install phi-agent openai python-dotenv

# Set up environment variables
# Create a .env file with the following:
# OPENAI_API_KEY=your_openai_api_key
# PHI_API_KEY=your_phi_api_key
# GROQ_API_KEY=your_groq_api_key
```

## Usage

### Running the Multi-Agent System

```bash
python financial_agent.py
```

This will demonstrate the multi-agent system analyzing NVIDIA (NVDA) stock, including analyst recommendations and latest news.

### Running the Interactive Playground

```bash
python playground.py
```

Access the playground interface in your browser at `http://localhost:8000` to interact with both the financial and web search agents.

## Agent Architecture

### Web Search Agent
- **Role**: Searches the web for up-to-date information
- **Tools**: Google Search, DuckDuckGo
- **Model**: LLaMA 3 70B (via Groq)

### Financial Agent
- **Role**: Analyzes financial data for specified stocks
- **Tools**: YFinance (stock prices, analyst recommendations, fundamentals, news)
- **Model**: LLaMA 3 70B (via Groq)

### Multi-AI Agent
- **Role**: Orchestrates both agents to provide comprehensive analysis
- **Tools**: All tools from component agents
- **Model**: LLaMA 3.1 70B Versatile (via Groq)

## Example Queries

- "Summarize analyst recommendations and share the latest news for NVDA"
- "Compare the financial performance of AAPL and MSFT"
- "Analyze recent trends in the tech sector and their impact on AMZN stock"
- "What are the current P/E ratios for top S&P 500 companies?"

## Customization

You can customize the agents by:
- Adding more tools to either agent
- Changing the model to a different provider
- Modifying the instructions for more specific outputs
- Adding additional agents for more specialized tasks

## License

[MIT License](LICENSE)

## Acknowledgments

- [Phi Framework](https://github.com/phi-ai/phi)
- [YFinance](https://github.com/ranaroussi/yfinance)
- [Groq](https://groq.com/)
