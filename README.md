## LangSearch-Agent-Streamlit
An interactive chatbot application that leverages Large Language Models (LLMs) and external search tools to provide accurate information. This project demonstrates the use of AI Agents to perform real-time web searching and academic research.

🚀 Features
- Autonomous Agent: Uses the ZERO_SHOT_REACT_DESCRIPTION agent type to reason and act.
- Multi-Tool Integration:
- DuckDuckGo Search: For general web queries and current events.
- Wikipedia: For summarized factual information.
- ArXiv: For searching academic papers and scientific research.
- Interactive UI: Built with Streamlit, featuring a real-time "thought process" expander using StreamlitCallbackHandler.
- Fast Inference: Powered by Groq using the Llama-3.1-8b-instant model.

🛠️ Tech Stack
- Framework: LangChain
- LLM: Llama 3.1 (via Groq Cloud)
- Frontend: Streamlit
- Tools: ArXiv API, Wikipedia API, DuckDuckGo Search
