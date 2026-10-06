# ⚡ Nexus AI - Modern Conversational Intelligence

A lightweight, high-performance, single-file ChatGPT-style web application powered directly by Google's official Gemini REST API. Designed with a sleek dark-mode UI, real-time response streaming, Markdown rendering, and dynamic model switching.

##✨ Key Features

🚀 Live SSE Streaming: Experience real-time token streaming direct from Google Gemini REST endpoints.

🎯 Multiple Model Support: Toggle between supported Gemini models seamlessly:

gemini-2.5-flash (Recommended for balance and speed)

gemini-2.5-pro (Advanced reasoning)

gemini-2.0-flash (Ultra-fast response generation)

🔒 Secure Local Storage: Your API Key and custom configuration stay local in your browser's localStorage—no middleman or backend server involved.

🎨 Modern Dark UI: Sleek sidebar navigation, dynamic conversation history, auto-resizing input area, and responsive design for both desktop and mobile.

📝 Code Highlighting & Copy: Rendered Markdown responses powered by Marked.js and syntax highlighted with Highlight.js, complete with one-click code copy buttons.

⚙️ Custom System Instructions: Custom prompt engineering with an editable temperature slider (creativity tuning).

📦 Zero Build Tooling Required: Pure single HTML file (index.html) using Tailwind CSS and FontAwesome CDN assets.

🛠️ Quick Start (Local Setup)

Clone or Download the Repository:

git clone https://github.com/YOUR_USERNAME/nexus-ai.git
cd nexus-ai


Run the Application:
Since Nexus AI is built as a self-contained single-page application (index.html), simply open index.html directly in any web browser!

Configure your API Key:

Click Settings & API Keys in the bottom-left sidebar.

Enter your Gemini API Key (obtain a free key at Google AI Studio).

Click Save Configuration.

☁️ Deployment Guide (GitHub to Vercel)

Nexus AI can be deployed to Vercel in under 60 seconds with zero backend configuration.

Step 1: Push code to GitHub

git init
git add index.html README.md
git commit -m "Initial commit of Nexus AI"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nexus-ai.git
git push -u origin main


Step 2: Deploy on Vercel

Log in to Vercel.

Click Add New > Project.

Import your nexus-ai repository from GitHub.

Keep the framework preset as Other / Static and click Deploy.

Your live app URL will be ready instantly with free SSL!

🔑 Security & API Key Management

[!WARNING]

Never commit hardcoded API keys directly into your GitHub repository!

Client-Side Storage: By default, Nexus AI asks the user to enter their API Key via the UI. The key is securely saved only in the visitor's web browser (window.localStorage).

Direct Requests: API calls are made directly from the user's browser client to https://generativelanguage.googleapis.com.

🔮 Roadmap & Cloud Sync (Firebase Setup)

Nexus AI is designed with optional Firebase integration for multi-device cross-platform synchronization.

Planned expansion:

[ ] Google OAuth / Firebase Authentication

[ ] Cloud Firestore history persistence across devices

[ ] Image uploading & Multimodal input support

📄 License

Distributed under the MIT License. See LICENSE for more information.
