# 🔥 CodeRed AI — by BorgworX™

**CodeRed AI** is a fire alarm layout and code compliance assistant built with OpenAI's Custom GPT framework, developed under the **BorgworX** initiative — merging field engineering with next-gen AI.

Designed for fire alarm installers, panel programmers, inspectors, and AHJs, it extracts device data from layout drawings and risers, interprets tabular entries, and provides field-accurate outputs aligned with NFPA 72.

---

## ⚙️ Features

- 🧠 Reads fire alarm **device tables** from images
- 🗂 Extracts structured, panel-ready device lists
- 🔄 Supports both **row-based** and **rotated column-stacked** formats
- 📚 Answers **NFPA 72** code questions (spacing, candela, pull station requirements, etc.)
- 📋 Outputs:
M1-91 | Smoke Detector | Photo | 2FL Corridor 113

yaml
Copy
Edit

---

## 👷 Who It's For

- 🔧 Installers & field techs
- 💻 Panel programmers
- 🕵️‍♂️ Inspectors and AHJs
- 🗂 Designers needing quick lookup & formatting

---

## 📁 Project Contents

| File | Description |
|------|-------------|
| `instructions.md` | Full assistant behavior logic |
| `description.txt` | Short Custom GPT bio (<300 chars) |
| `tool_schema.json` | GPT tool schema (optional) |
| `version_notes.md` | Changelog across iterations |
| `instructions_upload.txt` | Plain text copy for GPT builder UI |

---

## 🚦 Usage Instructions

> This repo defines a **Custom GPT configuration**, not code.

To use CodeRed AI:

1. Open [ChatGPT → Explore GPTs → Create](https://chat.openai.com/gpts/editor)
2. Paste contents of `instructions.md` into the **Instructions** field
3. Use `description.txt` as your GPT description
4. (Optional) Add `tool_schema.json` to enable parsing tools
5. Save it as your own version of CodeRed AI

---

## 🧪 Example Use Cases

- “Extract and format this fire alarm device table.”
- “How far apart do I need strobes in a hallway?”
- “Which of these addresses are used?”

---

## 🧠 About BorgworX™

**BorgworX™** is a high-performance AI systems lab founded by Jeff Cash, focused on bridging human expertise and machine efficiency. From smart homes to field AI, BorgworX solutions are built for clarity, precision, and edge-ready execution.

---

## 📜 License

This repository is currently private and maintained by BorgworX. Contact [Jeff](https://github.com/jlcash61) for usage, support, or licensing.
