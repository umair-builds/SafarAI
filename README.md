##SafarAI: 
Intelligent Travel & Expense Companion A specialized AI assistant that goes beyond general chat to act as a dedicated travel guide. It calculates precise travel expenses, distances, and estimated times of arrival for inter-city journeys by querying a structured SQL database, ensuring factual accuracy rather than hallucinations.

Agentic Architecture (Memory + Tools) Utilizes an advanced "Assistant" approach that maintains conversational memory (stateful chat) to understand context. It implements "Tool Use" (Function Calling) to perform actions beyond text generation, allowing the AI to dynamically fetch real-time data from a local SQLite database.

Hybrid Model Benchmarking (Local vs. Cloud) Built using the standard OpenAI SDK to seamlessly switch between local inference (Llama 3.2 via Ollama) and ultra-fast cloud inference (Groq). This setup demonstrates a comparative analysis of latency, accuracy, and cost between running models on edge devices versus the cloud.

Interactive Demo with Gradio Features a clean, user-friendly web interface built with Gradio that visualizes the AI's "thought process." It displays real-time streaming responses and explicitly shows when the AI triggers a "Tool Call," providing transparency and building user trust in the system's logic.
