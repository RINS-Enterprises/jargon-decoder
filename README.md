# 🧠 AI Jargon Decoder (n8n Workflow)

An AI-powered workflow that classifies user input and simplifies medical jargon into easy-to-understand language.

---

## 🚀 Overview

This system uses a multi-step AI workflow to detect whether a user message contains medical terminology and respond accordingly.

- If the input is medical → it simplifies the jargon  
- If the input is general → it responds as a friendly assistant  

---

## ⚙️ Tech Stack

- n8n (workflow automation)
- Google Gemini API (LLM)
- LangChain nodes (chat + agents)

---

## 🔄 System Flow

User Input → Intent Classification → Conditional Routing  
→ Medical Decoder OR Friendly Chat → Response Output  

---

## 🧩 Key Components

### 1. Intent Classifier (Bouncer)
- Classifies input as:
  - MEDICAL  
  - CHAT  
- Uses Gemini model with strict output rules  

---

### 2. Conditional Logic (IF Node)
- Routes requests based on classification result  
- Ensures correct AI agent handles the input  

---

### 3. Medical Jargon Decoder
- Translates complex medical terms into simple English  
- Uses:
  - short explanations  
  - analogies  
  - no technical jargon  

---

### 4. Friendly Chat Assistant
- Handles greetings and general queries  
- Explains system purpose in simple terms  

---

### 5. Response Output
- Returns final response to user via chat interface  

---

## 🎯 Purpose

- Make medical terminology understandable for non-experts  
- Provide a safe, non-diagnostic AI interaction  
- Demonstrate AI workflow design using LLM orchestration  

---

## 💡 Key Features

- Intent classification before response generation  
- Multi-agent architecture (specialized roles)  
- Controlled AI output using strict prompts  
- Lightweight and scalable workflow design  

---

## ⚠️ Notes

- This system does not provide medical advice  
- Designed for educational and demonstration purposes  

---

## 📦 Project Type

Workflow-based AI system built using n8n (JSON workflow included)

---

## 🚀 Status

Completed (functional workflow)

---
