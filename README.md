# 🤖 DeepSeek Local Chatbot

Run advanced AI models locally on Google Colab with Ollama server and Gradio UI!

## 🚀 Quick Start
1. Open in [Google Colab](your_colab_link)
2. Click `Runtime > Run all`
3. Chat using the provided link

## 🔧 Features
- Local model execution 🛡️
- Coding & general Q&A support 💻
- Simple 5-step setup 🛠️
- Free GPU acceleration 🚀

## 📦 Requirements
- Google Account
- Colab T4 GPU (Free tier compatible)

## 🚨 Troubleshooting
```bash
# Check server status
!curl http://localhost:11434

# Verify models
!ollama list

# Memory check
!free -h && nvidia-smi
