# Health_Agent
Health Agent – A Self-Evolving Wellness Companion

Inspiration
During a personal health transformation, I built a minimal but powerful AI agent that helps me track, and reflect on my health rhythm — including hydration, sleep, food, and movement. I realized I could automate my wellness workflow using an LLM-powered journaling assistant and make it accessible for others too.
🧠 What It Does 
Health Agent is a fully operational, AI-powered wellness companion that automates the cycle of health monitoring, reflection, and decision-making. It combines biometric data, personalized insights, and natural language querying into a seamless daily loop.
It can:

⌚ Connect to the Oura Ring API to retrieve sleep, readiness, and activity data.

📄 Store and structure health logs into a daily DataFrame with GPT-generated insights.

🧠 Embed data as memory using OpenAI embeddings and store them in a persistent vector database (Chroma).

🧾 Log daily summaries to Google Sheets for external tracking.

🤖 Query your past health records using natural language via a LangChain agent with GPT-4.

🌐 Offer a chat-style UI via Streamlit, hosted live using ngrok and Google Colab.
