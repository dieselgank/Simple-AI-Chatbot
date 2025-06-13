# 🤖 Chatbot AI Sederhana

Chatbot web sederhana menggunakan **OpenAI GPT-4o-mini** yang dibangun dengan **Node.js (Express)** dan frontend HTML/JS murni.

## 🔧 Fitur
- Kirim pesan ke AI (GPT-4o-mini)
- Tampilan UI minimalis
- API backend dengan Express.js

---

## 📦 Instalasi

```bash
git clone https://github.com/dieselgank/Simple-AI-Chatbot.git
cd Simple-AI-Chatbot
npm install
```
## 🔑 Konfigurasi API Key
Edit file server.js:
```bash
const openai = new OpenAI({
  apiKey:
    "YOUR_API_KEY", // Ganti dengan API Key dari OpenAI
});
```

💡 Daftar API key di https://platform.openai.com/api-keys

## 🚀 Menjalankan Aplikasi
```bash
node server.js
```
Buka browser ke ```http://localhost:3000```

## 🖥️ Tampilan Chatbot Sederhana
<p align="center">
  <img src="https://github.com/user-attachments/assets/b49117c2-8f79-4eca-a8a8-b284d7f92f4b" width="500" />
</p>
