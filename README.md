# Lora and MTL-Lora a new frontier of Multi-task  fine-tuning for LM
🚀 Medical Chatbot Fine-Tuning with LoRA & MTL-LoRA 🏥💡

🔍 Overview

This project pushes the boundaries of medical AI by fine-tuning the LLaMA 1B model using LoRA and our custom-built Multi-Task LoRA (MTL-LoRA) framework, designed from scratch in PyTorch.

📚 Phase 1: Fine-Tuning with PubMedQA

We enhance the model’s medical expertise with PubMedQA, leveraging:

⚡ LoRA: Efficient low-rank adaptation for faster, lightweight fine-tuning.

🛠️ Traditional Fine-Tuning: Updating only the last layer for controlled training.

📊 How We Evaluate

We compare three configurations: Base Model, LoRA-Tuned Model, and Traditionally Fine-Tuned Model using:

🎯 Perplexity

🏆 BLEU Score

📈 ROUGE Score

🤖 Phase 2: Custom Multi-Task LoRA (MTL-LoRA)

We built MTL-LoRA from scratch in PyTorch, allowing efficient multi-task learning across various medical NLP tasks in a single training pipeline. Inspired by cutting-edge research (arXiv 2410.09437), this approach ensures:

🚀 Seamless multi-task adaptation without retraining per task.

🔬 Enhanced generalization across diverse medical datasets.

💰 Reduced computational cost compared to full fine-tuning.

🌍 Join the Future of Medical AI!

Contribute, experiment, and push the boundaries of what’s possible in AI-driven healthcare! 🏥💙

