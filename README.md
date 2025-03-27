# playground
#   Phi Agent Playground

This project sets up an agent playground using the Phi library. It includes two agents: a web search agent and a financial agent.

##   Agents

###   Web Search Agent

* **Role:** Search the web for information
* **Model:** Groq (llama-3.2-90b-vision-preview)
* **Tools:** DuckDuckGo
* **Instructions:** Always include sources
* **Output:** Markdown

###   Financial Agent

* **Role:** Financial Agent
* **Model:** Groq (llama-3.2-90b-vision-preview)
* **Tools:** YFinanceTools (stock price, analyst recommendations, stock fundamentals, company news)
* **Instructions:** Use tables to display data
* **Output:** Markdown

##   Setup

1.  **Install Dependencies:**
    
    ```bash
    pip install python-dotenv phi-ai
    ```
    
2.  **Set Environment Variables:**
    
    * Create a file named `.env` in the project root.
    * Add your API keys to the `.env` file:
        
        ```
        PHI_API_KEY="your_phi_api_key"
        GROQ_API_KEY="your_groq_api_key"
        OPENAI_API_KEY="your_openai_api_key"
        ```
        
        * Replace `"your_phi_api_key"`, `"your_groq_api_key"`, and `"your_openai_api_key"` with your actual API keys. [cite: 1]
3.  **Run the Playground:**
    
    ```bash
    python your_script_name.py
    ```
    
    * Replace `your_script_name.py` with the name of your Python script.
