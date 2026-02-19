# 🤖 Local AI Companion: Edge-Side LLM Application

## 💡 Project Overview
A privacy-focused, low-latency AI companion application designed to run entirely on local hardware (AI PC). This project explores the limits of edge-side inference using consumer-grade hardware (Intel Core Ultra 7).

## ✨ Key Features
- **Local Inference:** Deployed quantized models (Llama-3/Gemma-2) using `Ollama` and `LM Studio`.
- **Hardware Acceleration:** Optimized for Intel Arc Graphics (iGPU) and NPU using OpenVINO / Vulkan offloading.
- **Long-term Memory:** Implemented RAG (Retrieval-Augmented Generation) using Vector Database (ChromaDB) for persistent user context.
- **Full-Stack Architecture:** Python (FastAPI) backend with an asynchronous architecture.

## 🔧 Architecture & Optimization
- **Model:** Llama-3-8B-Instruct (Quantized to Q4_K_M) / Gemma-2-9B
- **Inference Engine:** Ollama / llama.cpp
- **Hardware:** Intel Core Ultra 7 155H (32GB RAM)
- **Optimization:** KV Cache management, Layer offloading tuning.

## 🚧 Roadmap
- [x] Basic Local Inference Setup
- [ ] Python API Integration
- [ ] RAG Memory System Implementation
- [ ] Mobile Frontend (Flutter/React)
- [ ] NPU Acceleration with OpenVINO
