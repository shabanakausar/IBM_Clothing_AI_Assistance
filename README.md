# IBM_Clothing_AI_Assistance
Our project leverages **IBM Granite 3.2 8B LLM**, a powerful large language model, as the core engine behind the **AI Clothing Assistant**—a fashion recommendation application designed to provide intelligent, real-time outfit suggestions based on user preferences, geolocation-based weather, and budget.
SEO-optimized version of this paragraph for a project report, documentation, 

Here is an **SEO-optimized version** of the paragraph tailored for a **project report, documentation, or portfolio**. It emphasizes keywords like *AI clothing assistant*, *LangChain agent*, *local LLM*, *fashion recommendations*, and *Streamlit app* for better searchability:

---

### 🧠 Project Description: AI Clothing Assistant (IBM Granite 3 .2 8B LLM Model)

The **AI Clothing Assistant** is an intelligent, agent-based **fashion recommendation app** developed using IBM **Granite 3.2 8B model via Ollama. Locally  hosted *IBM Granite 3 .2 8B LLM via Ollama* is powered by LangChain agents. This application delivers personalized outfit suggestions by combining 
real-time weather data, 
user preferences, and 
a mock inventory database. 
It uses a conversational interface to help users find clothing items that match their 
style, 
location-specific weather, 
and budget.
Users can select a fashion style (e.g., minimalist, boho, casual, formal, or sporty) and adjust a budget slider to set spending limits. Additionally, a user dropdown allows the app to load pre-defined preferences, enhancing personalization through memory-assisted responses.

Users can customize their experience through a clean UI that features a **style dropdown**, **budget slider**, and **username selector**—allowing for optional preference memory.
The app automatically detects the user’s city using IP geolocation, then fetches live weather using the OpenWeather API.
Based on these inputs, the app crafts a dynamic prompt that is passed to a 'Granite 3 .2 8B LLM', which uses tools such as `get_weather`, `lookup_inventory`, and `load_user_preferences` to generate intelligent and context-aware responses.

The assistant leverages 'conversational agent architecture' and a **local LLM (Granite3.2:8B)** to ensure fast, secure, and cost-effective responses. All logic is handled through tool-calling capabilities, enabling the model to reason over structured data like clothing inventory and user-defined budgets.
The chat interface is built using `st.chat_message()`, offering a modern, chatbot-like experience with memory-powered multi-turn conversation support.

This AI Clothing Assistant is ideal for demonstrating the practical application of LLM agents in real-world use cases**, such as e-commerce, personalized styling, or digital fashion consulting. 
Its local-first design enhances **data privacy**, **low-latency performance**, and offline usability. 
Whether for enterprise deployment or personal productivity, this app exemplifies how to build **agentic AI systems with 'IBM Granite 3 .2 8B LLM', LangChain, Ollama, and Streamlit** for real-time, personalized, and tool-augmented user experiences.
