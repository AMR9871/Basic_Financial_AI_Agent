# Basic_Financial_AI_Agent
Technologies Used

1. Php-Data Structure

Agents: Uses the unaffiliated agent model to perform tasks.

Tools: Provides sources such as YFinance, DuckDuckGo and GoogleSearch to agents.

Models: Groq LLM is used here to your preferred processor and generator of responses.

2. It is focused on large Language Models (LLMs)

Groq Models:-

llama3-groq-70b-8192-tool-use-preview. Used for performing tasks which involve the need to search the web or am an analyst of finances.

llama-3.1-70b-versatile. This is the primary model which controls the multi-agent cooperation and is the common aspect of various queries raised by users.

3. Financial Data Tools

YFinanceTools:

Provides Up to the minute stock prices, projections made by analysts, fundamentals of the organization, and the prevailing news related to it.

Gives financial data in an organized manner i.e. Makes sure that data is presented in a neat categorical manner with tables.

4. Web Search Tools

DuckDuckGo and GoogleSearch:

Use of websites to search for other information that may not be related to finance.

Make sure that the sources are directly quoted (e.g., say from DuckDuckGo or Google).

5. Environment Management

dotenv: Handles API Keys and environment variables in a safe manner.

openai API: Portends chances of expansion of Open AI functionalities.
<br>

System Features

Multi-Agent System:

Utilizes multiple agents (web_search_agent and finance_agent) for performance improvement by delegating several functions.

Employs a single multi_ai_agent to assume the task of coordinating possibly all agents.

Tool-Augmented AI:

Each agent has its set of roles and comes with tools (e.g., YFinanceTools provides financial information, DuckDuckGo provides search results).

It helps in producing more accurate and thorough information.

Interactive Responses:

Information is streamed to the users instead of locking the user in a single point which enhances the experience.

Sources provided is a markdown formatted structure thus is presentably structured and clear.

Source Attribution:

Provides source links to documents where information was obtained thus promoting adopting sense of accountability from the users.

Financial Insights:

Contains such analyst ratings, stock price quotes, additional company news, which can be helpful for analysts and decision makers.

Applications

Conducting financial analysis and taking investment decisions.

Providing synopsis of financial news and other relevant trends.

Conducting background research for companies/individuals on automatic mode.

Creating supportive instruments for investors in the stock market.

<br>
With the combination of agentic AI and specialized tools and models, this project shows a great potential for automation of advanced tasks related to financial analysis and research.
