<div align="center">

# 🚀 **3DOS AUTOMATION BOT**
### *Stealth • Anti-Detection • Proxy Rotation • API Automation • Multi-Platform*

<hr>

</div>

3DOS BOT is a fast, modular, stealth-focused Node.js automation tool designed for APIs, sessions, tokens, proxies, and advanced anti-detection workflows.

---

# 🛠 Installation (Start Here)

## 📥 Clone the Repository
```bash
git clone https://github.com/vaib90/3DOS_BOT.git
```

## 📂 Enter Project Directory
```bash
cd 3DOS_BOT
```

## 📦 Install Dependencies
```bash
npm install
```

---

# 🌐 Add Proxies
Open proxy file:
```bash
nano proxy.txt
```

Add proxies in this exact format (one per line):
```
http://username:password@ip:port
http://user:pass@123.45.67.89:8080
http://12.34.56.78:3128
```

Save file: **CTRL + X → Y → Enter**

---

# 🔐 Add Access Token
Open token file:
```bash
nano token.txt
```

Paste your access token:
```
your-access-token-here
```

Save: **CTRL + X → Y → Enter**

---

# 🔍 How to Find Your Access Token

## 📱 Android Phone Users  
Supported browsers: **Kiwi Browser**, **Mises Browser**

### Steps:
1. Login to your **3DOS account**  
2. Open **Developer Mode**  
   - Kiwi → Menu → Developer Tools → Inspect  
   - Mises → Settings → Developer Options → Web Inspector  
3. Navigate:  
   **Application → Local Storage**  
4. Select your domain  
5. Look for key:
   ```
   access_token
   ```
6. Use a 3rd-party text copy app for long values  
7. Paste into `token.txt`

---

## 🖥 Desktop Users (Windows / Linux / macOS)
1. Open Chrome / Edge / Brave  
2. Press **F12** to open DevTools  
3. Go to:  
   **Application → Local Storage → Your Domain**  
4. Find key:
   ```
   access_token
   ```
5. Copy the value → paste into `token.txt`

Desktop users get it easily ✔

---

# ▶️ Run the Bot
```bash
node main.js
```

---

# 🧩 Features
- 🔥 Automated API execution  
- 🛡 Advanced anti-detection  
- 🌐 Proxy rotation system  
- 📦 Modular architecture  
- 🧠 Configurable workflow  
- 📱 Works on Termux, Android, Windows, Linux, macOS  

---

# 📁 Project Structure
```
3dos/
├── core/
├── config/
├── utils.js
├── main.js
├── setup.js
├── tokens.txt
├── proxy.txt
├── localStorage.json
├── session_user_agents.json
└── package.json
```

---

# 📜 License
This project is licensed under the **MIT License**.

---

# 🤝 Contribution  
Pull requests are welcome.  
For major changes, please open an issue first.
