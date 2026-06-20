# 🛡️ SecureAudit.ai

**AI-powered security code auditor for Node.js / Express / PostgreSQL applications.**

Paste your code, get an instant OWASP Top 10 security audit — vulnerable code highlighted, root cause explained, and a ready-to-use fix for every issue.

---

## 🔴 Live Demo — Use It Now

### 👉 **[Launch SecureAudit.ai](https://cyberwolf6938.github.io/CodeAlpha_SecureAudit-ai/)**

No installation. No setup. Just open the link, paste your free API key, and start auditing.

---

## ✨ Features

- 🔍 **OWASP Top 10 Detection** — SQL Injection, IDOR, Broken Authentication, Hardcoded Secrets, Weak Crypto, XSS, and more
- 📊 **Risk Score Dashboard** — instant 0–100 risk rating with severity breakdown
- 🧩 **Detailed Findings** — vulnerable code, root cause, proof-of-concept, and exact remediation code for every issue
- 🗺️ **Prioritized Roadmap** — Week 1 / Month 1 / Long-term action plan
- 🔧 **SAST/SCA Tool Recommendations** — exact CLI commands for tools like Semgrep, ESLint security plugins, and npm audit
- 📦 **Dependency Report** — outdated and vulnerable package detection
- ✅ **Secure Coding Best Practices** — tailored to your code
- 🔑 **Bring Your Own API Key** — your key, your privacy, never stored or logged

---

## 🚀 How to Use

1. Open the **[live tool](https://cyberwolf6938.github.io/CodeAlpha_SecureAudit-ai/)**
2. Get a **free Gemini API key** → [aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
3. Paste your key into the tool
4. Paste your Node.js code (or upload a `.js` file)
5. Click **Run Security Audit**
6. Review findings, fixes, and your remediation roadmap

> 🔒 **Privacy:** Your API key stays in your browser memory only. It is never saved, stored, or sent anywhere except directly to Google's Gemini API.

---

## 🖼️ Preview

| Findings Dashboard | Remediation Detail |
|---|---|
| Risk score, severity counts, and filterable findings list | Vulnerable code, root cause, fix code, and test steps |

---

## 🧠 What It Detects

| Category | Examples |
|---|---|
| Injection | SQL Injection, Command Injection |
| Authentication | Broken Auth, Insecure JWT, Weak Password Handling |
| Access Control | IDOR, Missing Authorization |
| Secrets | Hardcoded API Keys, Hardcoded Passwords |
| Cryptography | Weak Hashing, Insecure Random |
| Data Exposure | Information Disclosure, Verbose Errors |

---

## 🛠️ Tech Stack

- **Frontend:** Pure HTML, CSS, JavaScript (no frameworks, no build step)
- **AI Engine:** Google Gemini API (`gemini-2.5-flash`)
- **Hosting:** GitHub Pages (free, static)
- **API Proxy:** Vercel Serverless Function (free tier) — solves browser CORS restrictions

---

## 📁 Project Structure

```
CodeAlpha_SecureAudit-ai/
├── index.html        # The complete tool — UI + logic in one file
└── README.md          # You are here
```

A companion repo, `secureaudit-proxy`, hosts the lightweight serverless function that securely forwards requests to the Gemini API.

---

## 💻 Run It Locally

No build tools required:

```bash
git clone https://github.com/cyberwolf6938/CodeAlpha_SecureAudit-ai.git
cd CodeAlpha_SecureAudit-ai
open index.html
```

Or simply double-click `index.html` in your file explorer.

---

## 🎓 Use Cases

- ✅ **University Projects** — demonstrates OWASP Top 10 concepts with real, explainable findings
- ✅ **Portfolio Showcase** — a polished, working AI security tool for recruiters to see live
- ✅ **Developer Utility** — quick sanity-check for Express routes before pushing to production

---

## ⚠️ Disclaimer

This tool provides AI-generated security analysis for educational and reference purposes. It is **not a replacement** for professional penetration testing, manual code review, or established SAST/SCA tools in a production security pipeline. Always verify findings before applying fixes to production code.

---

## 📄 License

MIT License — free to use, modify, and share.

---

## 👨‍💻 Author

Built by **CYBERWOLF**
🔗 [LinkedIn](www.linkedin.com/in/faiz-uddin-8bbb39348) · 🐙 [GitHub](https://github.com/cyberwolf6938)

---

⭐ If you found this useful, consider giving the repo a star!
