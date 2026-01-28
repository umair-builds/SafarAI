🚀 SafarAI – Intelligent Travel & Expense Companion

SafarAI is a specialized AI assistant designed to act as a reliable travel guide, focusing on factual accuracy rather than generic chat responses. It calculates travel expenses, distances, and estimated arrival times for inter-city journeys by querying a structured SQL database instead of relying on model guesswork.

🧠 Agentic Architecture (Memory + Tools)

SafarAI follows an agent-based design with:

Stateful conversational memory to maintain travel context across turns

Tool / Function Calling to dynamically query a local SQLite database

Deterministic responses grounded in structured data, minimizing hallucinations

⚡ Hybrid Model Benchmarking (Local vs Cloud)

The system supports dynamic model switching using the OpenAI SDK:

Local inference: Llama 3.2 via Ollama (edge-device friendly)

Cloud inference: Groq for ultra-low latency responses

This enables direct comparison of:

Latency

Accuracy

Cost efficiency

🎛 Interactive Demo with Gradio

SafarAI includes a clean Gradio-based web interface that:

Streams responses in real time

Visualizes the AI’s reasoning flow

Explicitly shows when a tool call is triggered

Improves transparency and user trust in AI decisions

🛠 Tech Stack

Python

OpenAI SDK

Llama 3.2 (Ollama)

Groq

SQLite

Gradio
