
# Agents-Tools-who-can-search-the-web

Agents and Tools using the LangChain framework, and here's a quick overview :

Wikipedia and Arxiv Queries: I set up tools to pull concise information from Wikipedia and Arxiv using WikipediaQueryRun and ArxivQueryRun. These tools are handy for fetching targeted data quickly.

Custom Retriever Tool: I built a custom search tool using WebBaseLoader and FAISS. This tool allows for efficient searching over specific documents, enhancing the retrieval process with OpenAIEmbeddings.

ChatGroq: I integrated the ChatGroq model, enabling interaction with the tools . This setup allows for dynamic querying based on user input

Agent and AgentExecutor: I created an agent using create_openai_tools_agent and executed it with AgentExecutor. This agent can intelligently use tools to answer queries
