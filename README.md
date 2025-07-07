

# 🍲 Indian Recipe Generator - Qwen2.5 3B (Fine-tuned)

A fine-tuned version of [Qwen/Qwen2.5-3B-Instruct](https://huggingface.co/Qwen/Qwen2.5-3B-Instruct) trained to generate Indian recipes based on ingredients provided by the user. This model uses **Unsloth + QLoRA** for efficient memory usage and faster training.

Developed by [@bnaveenbharathi](https://huggingface.co/bnaveenbharathi).

---

## 💡 Use Case

Give the model a list of ingredients (like "tomato, paneer, onion") and it will respond with step-by-step Indian recipes — perfect for cooking apps, kitchen bots, or personal food assistants.

---

## 🧠 Model Details

- 🔸 **Base model:** [Qwen/Qwen2.5-3B-Instruct](https://huggingface.co/Qwen/Qwen2.5-3B-Instruct)
- 🔸 **Fine-tuned with:** [Unsloth](https://github.com/unslothai/unsloth) using QLoRA
- 🔸 **Dataset:** Custom dataset of Indian ingredients and responses
- 🔸 **Epochs:** 3  
- 🔸 **Quantization:** 4-bit, LoRA merged into base model  
- 🔸 **Max sequence length:** 512

---
