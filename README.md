# AI-Nutrition_Agent
# 🥗 Nutrition Agent – AI-Powered Virtual Nutrition Assistant

This project was developed as part of the **IBM Edunet Foundation Virtual Internship** using **IBM Watsonx.ai**. The goal was to create an intelligent AI assistant that delivers personalized nutrition advice to users based on their health goals, dietary needs, and preferences.

---

## 📌 Project Overview

The **Nutrition Agent** is a fully cloud-hosted, AI-powered assistant that helps users:
- Generate customized meal recommendations
- Explain food choices based on nutrition goals
- Suggest healthier alternatives
- Adapt responses based on allergies and dietary restrictions

Built using **IBM Watsonx.ai Agent Lab**, the agent uses vector-based memory and a large language model to retrieve answers grounded in nutritional data.

---

## 🧠 Model & Tools Used

| Technology           | Purpose                                              |
|----------------------|------------------------------------------------------|
| 🧠 **Mistral Large**       | Main generative AI model (LLM) inside Watsonx       |
| 📊 **Nutrition Dataset**   | Vectorized dataset used for grounding responses     |
| 🧩 **Document Search Tool**| RAG-style retrieval based on user query context     |
| ☁️ **IBM Cloud Lite**      | Cloud environment to host and manage the entire agent |

---

## 🤖 Agent Capabilities

1. Understands natural language queries about:
   - Meal planning
   - Dietary needs
   - Health goals
2. Responds with:
   - Personalized meals (e.g., high-protein, low-carb)
   - Nutritional explanations (e.g., calories, macros)
   - Allergy-safe options
3. Uses vector memory to ground responses on nutrition facts
4. Refuses unrelated questions outside the nutrition domain

---

## 🚀 Deployment Info

- Platform: **IBM Watsonx.ai Agent Lab**
- Deployment Type: **Fully hosted on IBM Cloud (no backend used)**
- Model: `mistral-large` (pre-configured in Watsonx project)
- Dataset used: **Single nutrition dataset** uploaded via document vector store
- Integration: Optionally connected to WhatsApp using Twilio (if required)

---

## 🏁 Internship Alignment

This project addresses:

> **Problem Statement 8 – Nutrition Agent**  
> "Build an intelligent, adaptive virtual assistant that uses generative AI to provide dynamic meal planning, food explanations, and personalized nutritional guidance."

---

## 📄 Project Highlights

- ✅ Fully no-code solution using Watsonx Agent Lab
- ✅ Context-aware generative responses using vector indexing
- ✅ Uses **Mistral Large** model for reasoning and explanation
- ✅ Personalized AI interaction without any local backend

---

## 👤 Developed by

**Mudike Navitha**  
MSc Data Science – University College of Science, Osmania University  
IBM Virtual Intern – AI & Cloud Computing  

---

## 📜 License

This repository is part of the IBM SkillBuild Virtual Internship 2025. All files and logic are created for educational and demonstration purposes only.

