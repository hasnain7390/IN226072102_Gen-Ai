Chatbot using Transformers (DialoGPT)
📌 Project Overview
This project demonstrates the implementation of a conversational chatbot using Hugging Face Transformers and DialoGPT. The chatbot is capable of generating human-like responses and maintaining context across multiple turns in a conversation.

🚀 Features
Interactive command-line chatbot
Context-aware conversation handling
Built using pre-trained Transformer model (DialoGPT)
Clean and modular code structure (class-based implementation)
Supports continuous conversation until user exits
🛠️ Technologies Used
Python
Hugging Face Transformers
PyTorch
DialoGPT (microsoft/DialoGPT-medium)
⚙️ Installation
Install required libraries:

pip install transformers torch

▶️ How to Run
Open the notebook or Python file
Run all cells / execute the script
Start chatting with the bot
Example:

You: hello
Bot: Hi, good to see you here!

You: what is AI
Bot: Artificial Intelligence

You: exit
Bot: Goodbye! 👋

🧠 How It Works
User input is tokenized using DialoGPT tokenizer
Input is appended to conversation history
Model generates response using Transformer architecture
Output is decoded into human-readable text
📊 Model Details
Model: "microsoft/DialoGPT-medium"
Architecture: GPT-based conversational model
Trained on large-scale dialogue datasets
Capable of multi-turn conversation
⚠️ Notes
Model responses may vary as it is probabilistic
Requires internet for first-time model download
Performance depends on system/Colab runtime
🎯 Conclusion
This project demonstrates how powerful Transformer models can be used to build intelligent conversational systems with minimal effort. It provides a strong foundation for developing advanced AI chatbots.

🙌 Acknowledgement
Thanks to Hugging Face and Microsoft for providing pre-trained models like DialoGPT.

