# 🐉 Kali GPT Clone – Offensive Security Assistant

> **Status:** ✅ Fully Functional  
> **Created by:** Mario Protopapa - DeBuG
> **Inspired by:** Kali GPT (custom GPT by Marc Streefland / XIS10CIAL)

## 📘 Overview

This repository contains a complete, functional **AI assistant clone** of Kali GPT – the custom AI built for offensive and defensive cybersecurity training, using Kali Linux toolsets.

It integrates:
- A full system prompt replicating Kali GPT's behavior
- Three dynamic Function Calling tools
- A practical Knowledge Base composed of documents **originally used by Kali GPT itself**

---

## 3. Knowledge Base

PDF and DOCX files used by Kali GPT for reasoning and responses:

| File Name                                                               | SHA256 Hash                                                                                         |
|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Advanced Security Testing with Kali Linux.pdf                           | `ad77c9e99e103f7e41a0d66b5153f1c72cf67e4109e00809b2a8bf91fc2f58c3`                                   |
| Knowledge File Kali Linux Repositories.docx                             | `6cbaeaccb40ea7d3abf5a776e2d0455d4f99fc8a5de3392fe7b6fe61703e3c31`                                   |
| Kali Linux Knowledge File - Software - December 2024 Updates.docx       | `3050af64ada2dcf66ea8ae2f6056982f56cb954ecd777faca40ceaa016438053`                                   |

> **Integrity Check:** Verify file authenticity by comparing SHA256 hashes.

---

## 🐉 Prompt for Automatic Verification via Kali GPT

To verify the files using Kali GPT, use this prompt:

![image](https://github.com/user-attachments/assets/bfb77e79-9302-4b59-b3b3-e5760c89f5ae)

---

## 📂 Included Files

### 🔹 Prompt
- `kali_gpt_clone_prompt.yaml`  
> System behavior, ethics, tooling, and supported phases (recon, exploit, post, defense, report)

### 🔹 Function Tools (JSON)
- `function_schema.json`
  - `ScriptExplain(script_text, language)`
  - `ToolUsage(tool_name, mode)`
  - `LabSim(objective, phase)`

### 🔹 Knowledge Base
These files were actively used by **Kali GPT** in the reasoning and response generation process:

- `Advanced Security Testing with Kali Linux.pdf`
- `Knowledge File Kali Linux Repositories.docx`
- `Kali Linux Knowledge File - Software - December 2024 Updates.docx`

They include advanced methodologies, updated tooling knowledge, and repository configurations drawn from real-world scenarios.

---

## ⚙️ Function Tool Descriptions

| Function       | Description                                       |
|----------------|---------------------------------------------------|
| `ScriptExplain`| Line-by-line script analysis (bash, py, ps)       |
| `ToolUsage`    | Command generation + simulated output for tools   |
| `LabSim`       | Step-by-step lab simulation of cyber kill chains  |

---

## 🚀 Use Cases

- Penetration testing simulations  
- Red/Blue team lab training  
- Scripting and exploit analysis  
- Offensive security education  
- Forensics and incident response

---

## 🔐 Ethics & Legal

This assistant **strictly enforces ethical usage**. It is designed for:
- Educational use only
- Lab-based testing environments
- Professional development in cybersecurity

❌ Not for real-world unauthorized use.

---

## 🧠 Powered by

- OpenAI GPT-4 Function Calling
- Kali Linux methodologies
- Custom KB-driven prompting

---

## 📎 Credits

- Original GPT concept by **Marc Streefland (XIS10CIAL)**  
- Kali Linux by Offensive Security  
- Knowledge files sourced from documents **used by Kali GPT** during technical support

---

> 💬 Want help setting up your own cybersecurity AI agent? Fork this repo and reach out!
