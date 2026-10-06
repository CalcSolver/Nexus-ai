⚡ Nexus AI — Modern Conversational Intelligence
A lightweight, high‑performance, single‑file ChatGPT‑style web application powered directly by Google’s official Gemini REST API.
Built with a sleek dark‑mode UI, real‑time streaming, Markdown rendering, and dynamic model switching — all inside one HTML file.

🚀 Features at a Glance
🔥 Real‑Time SSE Streaming
Experience smooth, live token streaming directly from Gemini REST endpoints.

🎯 Multiple Model Support
Switch between supported Gemini models instantly:

gemini‑2.5‑flash — Best balance of speed + intelligence

gemini‑2.5‑pro — Advanced reasoning

gemini‑2.0‑flash — Ultra‑fast responses

🔒 Secure Local Storage
Your API key stays only in your browser via localStorage.
No backend. No server. No risk.

🎨 Modern Dark UI
Responsive layout, sidebar navigation, conversation history, auto‑resizing input, and mobile‑friendly design.

📝 Markdown + Code Highlighting
Powered by Marked.js + Highlight.js, including one‑click code copy buttons.

⚙️ Custom System Instructions
Editable system prompt + temperature slider for creativity control.

📦 Zero Build Tools Needed
A single index.html using TailwindCSS + FontAwesome CDNs.
No bundlers. No Node. No setup.

🛠️ Quick Start (Local Setup)
1️⃣ Clone the Repository
bash
git clone https://github.com/YOUR_USERNAME/nexus-ai.git
cd nexus-ai
2️⃣ Run the App
Just open index.html in any browser — that’s it.

3️⃣ Add Your API Key
Open Settings → API Keys

Paste your Gemini API key (get one free at Google AI Studio)

Click Save Configuration

☁️ Deploying to Vercel (60 Seconds)
1️⃣ Push to GitHub
bash
git init
git add index.html README.md
git commit -m "Initial commit of Nexus AI"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nexus-ai.git
git push -u origin main
2️⃣ Deploy on Vercel
Log in to Vercel

Click Add New → Project

Import your GitHub repo

Framework preset: Other / Static

Click Deploy

Your live URL appears instantly — with free SSL.

🔑 Security & API Key Management
⚠️ Never commit your API key to GitHub.

Nexus AI uses client‑side storage only:

API key saved in localStorage

Requests sent directly from browser → https://generativelanguage.googleapis.com

No backend server involved

This keeps your key private and secure.

🔮 Roadmap — Optional Firebase Cloud Sync
Future planned features:

[ ] Google OAuth / Firebase Authentication

[ ] Cloud Firestore conversation syncing

[ ] Image uploads + multimodal input

These will allow multi‑device history and advanced AI interactions.

📄 License
Distributed under the MIT License.
See LICENSE for full details.
