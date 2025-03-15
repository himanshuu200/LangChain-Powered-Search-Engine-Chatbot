# LangChain-Powered-Search-Engine-Chatbot
This project is a search engine chatbot built using LangChain, designed to answer user queries by searching the web, retrieving research papers from arXiv, and fetching information from Wikipedia. Powered by the Groq API and the Llama3-8b-8192 model, the chatbot provides real-time, conversational responses to complex questions.

# Features:

Web Search: Utilizes DuckDuckGo Search to find relevant information from the web.

arXiv Integration: Fetches and summarizes research papers for academic queries.

Wikipedia Integration: Retrieves concise information from Wikipedia.

Conversational AI: Leverages the Llama3-8b-8192 model for natural, interactive responses.

Streamlit Interface: Provides a user-friendly web interface for seamless interaction.

# Tech Stack:

LangChain: For agent orchestration and tool integration.

Groq API: For fast and efficient LLM inference.

Streamlit: For building the interactive web app.

arXiv API, Wikipedia API, and DuckDuckGo Search: For real-time data retrieval.

# How It Works:

Users input their queries via the Streamlit interface.

The chatbot uses LangChain to determine the best tool (web search, arXiv, or Wikipedia) to answer the query.

The Groq API processes the query using the Llama3-8b-8192 model and generates a response.

The response is displayed in the chat interface, along with relevant summaries or links.

# Future Enhancements:

Add more data sources (e.g., news APIs, scientific databases).

Improve the chatbot’s reasoning and multi-step query handling.

Enhance the UI/UX with additional features like saved queries or history.

Feel free to contribute, suggest improvements, or use this project as a reference for building your own AI-powered search tools!
