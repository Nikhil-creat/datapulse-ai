# DataPulse AI · Nikhil Chary Sriramoju
Static portfolio and mission control: Nova assistant (offline portfolio Q&A, plus Groq tool-calling agent), Agent Missions, Data Lab, RAG Vault, in-browser CNN, terminal, live GitHub stats.
Add a free Groq key in Settings (https://console.groq.com/keys). It stays in your browser. Never commit keys.
Models are auto-detected from your key (llama-3.3-70b-versatile was retired by Groq on 2026-08-16).
Deploy: GitHub Pages, branch main, folder /root. Docker: `docker build -t datapulse . && docker run -p 8080:80 datapulse`
