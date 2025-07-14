# PRODIGY_GEN-AI_01
# 🧠 GPT-2 Text Generation with Hugging Face Transformers

This project demonstrates how to generate text using OpenAI's GPT-2 model with the Hugging Face `transformers` library and PyTorch.

## 📋 Requirements

Make sure you have Python 3.6+ installed. Then install the required packages:

```bash
pip install transformers torch
🚀 Description
This script performs text generation in two ways:

1. Greedy decoding – picks the most likely next token at each step.

2. Sampling with temperature – allows more randomness in the output.

📌 Features
Loads the pre-trained GPT-2 model and tokenizer.

Encodes a prompt string.

Generates text using both greedy decoding and sampling.

Utilizes GPU if available for faster generation.
📄 Notes
The pad_token_id is set to eos_token_id to suppress warnings.

attention_mask is passed to ensure proper handling of padded inputs.

You can modify the prompt and generation settings as desired.

📦 Output Example
I enjoy walking with my cute dog, but I also enjoy...

🧠 Concepts
Greedy Decoding: Selects the highest probability token each time.

Temperature Sampling: Introduces randomness; lower values (e.g., 0.7) make output more conservative.

✅ Usage
Run the script in any Python environment that supports PyTorch, such as:
 
Google Colab

Jupyter Notebook

VS Code
