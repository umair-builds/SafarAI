# 🚀 SafarAI
## Intelligent, Agentic Travel & Expense Companion

SafarAI is a specialized AI assistant designed to deliver **accurate, data-driven travel insights**. Unlike generic chatbots, it computes **inter-city travel costs, distances, and ETAs** by querying structured databases instead of relying on probabilistic text generation.

---

## 🧠 Agentic Architecture (Memory + Tools)

SafarAI uses a stateful, agent-based architecture with conversational memory and tool/function calling. This enables the system to understand context, execute database queries, and return deterministic, explainable results while minimizing hallucinations.

---

## ⚡ Hybrid Inference (Local vs Cloud)

SafarAI supports dynamic model switching using the OpenAI SDK:
- **Local inference:** Llama 3.2 via Ollama  
- **Cloud inference:** Groq for ultra-low latency  

This setup enables benchmarking of latency, accuracy, and cost across edge and cloud deployments.

---

## 🎛 Interactive Demo (Gradio)

SafarAI includes a clean Gradio web interface featuring real-time streaming responses and explicit visualization of tool calls, improving transparency and user trust in the system’s reasoning.

---

## 🧩 Tech Stack

Python · OpenAI SDK · Llama 3.2 (Ollama) · Groq · SQLite · Gradio
