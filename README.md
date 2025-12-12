# 🔒 LLM-SEC — AI Security Scanner (v1.0)

LLM-SEC is a lightweight, cross-platform security scanner designed to test Large Language Models (LLMs) for vulnerabilities using adversarial prompts, jailbreak sequences, and safety-evasion payloads.

Inspired by tools like SQLMap, but built for LLM Offensive Security.

---

## ✨ Features

- 🚀 900+ curated adversarial prompts  
- 🔥 Smart Auto-Detection Mode  
- 🖥️ Works on Windows, Linux, macOS  
- 🎨 Dynamic ANSI Banner (SQLMap-style)  
- 🌐 Burp Proxy support  
- 📊 Generates HTML + JSON security reports  
- 🧠 Detects jailbreaks, refusals, policy bypass  
- 📡 Supports OpenAI, LM Studio, Ollama, Jan, custom API  

---

## 📦 Installation

### 1. Clone the Repo
git clone https://github.com/YOUR_USERNAME/LLM-SEC.git

cd LLM-SEC

### 2. Install Dependencies

pip install -r requirements.txt


---

## ▶️ Usage

Run:

python llm-sec.py


Follow the on-screen prompts.

---

## 🧪 Burp Suite Proxy (Optional)

Set **Use Burp? → y** when starting the tool.

Traffic automatically routes through:
http://127.0.0.1:8080 (BurpSuite Proxy)


---

## 📝 Output

Reports saved under:

reports/


Each run generates:

- `.json`
- `.html`
- `.txt` (console log)

---

## 📁 Probes

All adversarial payloads are stored in:

probes/

You can add new ones easily.

---

## 📜 License
MIT License

---

## 🤝 Contributing

Pull requests are welcome!


