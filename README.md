# 🎙️ Voice-to-Sheets E-Commerce Product Loader
<img width="1920" height="1080" alt="addprod_autom" src="https://github.com/user-attachments/assets/911e0f71-176f-4834-8f9d-c4db63c3ce6a" />

An AI-powered pipeline that converts unstructured voice descriptions into formatted database entries.

## 🚀 Problem & Solution
* **Problem:** Surplus clothing sellers refused to join my e-commerce marketplace. Because their inventory consists of unique, single-stock items, manually entering data (category, price, description) for every single product was too time-consuming for them.
* **Solution:** I built a voice-operated workflow. Sellers simply dictate the product details, and the AI automatically extracts, structures, and uploads the data into the database, completely eliminating the manual entry friction.

## ⚙️ How It Works
1. **Audio Capture:** Receives product voice notes via Webhook.
2. **Speech-to-Text:** Transcribes audio to raw text using **OpenAI Whisper**.
3. **Data Extraction:** Uses **OpenAI GPT** to parse unstructured text into a strict **JSON** format.
4. **Data Export:** Automatically populates the structured data into **Google Sheets**.

## 🛠️ Tech Stack
**Make.com | OpenAI API (Whisper & GPT) | JSON | Google Sheets API**
