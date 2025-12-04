# Medical-VQA-Chatbot-MSc-Nilesh
multi-turn medical VQA system that integrates open-source vision-language and language models to perform image-based question answering, conversational reasoning, clinical summarisation, and diagnostic suggestion.
Medical Visual Question Answering (Med-VQA) System — Multi-Model Pipeline

This repository contains the full implementation of a multimodal Medical VQA chatbot developed for an MSc dissertation project. The system integrates:

Finetuned BLIP-VQA model for visual question answering

LLaMA-based conversational reasoning

FLAN-T5 summarisation module

ChatGPT (OpenAI) and Gemini (Google) paid APIs for enhanced VQA

Evaluation framework for quantitative and qualitative comparison among models

The project demonstrates a multi-turn, image-grounded medical assistant capable of analysing radiology images, answering clinical questions, producing structured summaries, and suggesting diagnostic reasoning outputs.

📁 Repository Structure
/project-root
│
├── 1_data_preprocessing
├── 2_model_finetuning
├── 3_final_finetuned_blip_GUI
├── 4_chatgpt_api_model
├── 5_gemini_api_model_GUI
├── 6_evaluation_metrics
│
├── README.md
└── requirements.txt

🔍 Project Overview
Objective

To develop a modular, open-source Medical Visual Question Answering system integrating VLMs and LLMs to support:

Image-based VQA

Multi-turn clinical conversation

Summarisation of radiology discussions

Basic diagnostic suggestion

Models Used
Task	Model
Visual Question Answering	BLIP-VQA-Base (finetuned)
Dialogue	LLaMA (small variant)
Summarisation	FLAN-T5 (small)
Diagnostics Reasoning	LLaMA (small)
API Models	ChatGPT-4o, Google Gemini Vision
🚀 Features

Upload any medical image (X-ray/CT/MRI)

Ask clinical questions and receive grounded answers

Multi-turn dialogue with memory

Automatic session summarisation

Diagnostic/treatment suggestion module

Evaluation dashboard comparing:

Finetuned BLIP

ChatGPT

Gemini
