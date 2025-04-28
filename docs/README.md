# 🔥 CodeRed AI — by BorgworX™

**CodeRed AI** is a fire alarm layout and code compliance assistant built with OpenAI's Custom GPT framework, developed under the **BorgworX** initiative — merging field engineering with next-gen AI.

Designed for fire alarm installers, panel programmers, inspectors, and AHJs, it extracts device data from layout drawings and risers, interprets tabular entries, and provides field-accurate outputs aligned with NFPA 72.

---

## ⚙️ Features

- 🧐 Reads fire alarm **device tables** from images
- 🗂 Extracts structured, panel-ready device lists
- 🔄 Supports both **row-based** and **rotated column-stacked** formats
- 📚 Answers **NFPA 72** code questions (spacing, candela, pull station requirements, etc.)
- 📋 Outputs clean, consistent entries:

```markdown
M1-91 | Smoke Detector | Photo | 2FL Corridor 113
```

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

> This repo defines a **Custom GPT configuration**, not executable code.

To deploy CodeRed AI:

1. Open [ChatGPT → Explore GPTs → Create](https://chat.openai.com/gpts/editor)
2. Paste the contents of `instructions.md` into the **Instructions** field
3. Use `description.txt` for the GPT description
4. (Optional) Add `tool_schema.json` if parsing tools are needed
5. Save and publish your customized version

---

## 🧪 Example Use Cases

- “Extract and format this fire alarm device table.”
- “How far apart must hallway strobes be placed?”
- “Which addresses are already assigned in this matrix?”

---

## 🧑‍💻 About BorgworX™

**BorgworX™** is a high-performance AI systems lab founded by Jeff Cash, focused on bridging human expertise and machine efficiency. From smart buildings to field-ready AI, BorgworX solutions are built for clarity, precision, and edge execution.

---

## 📜 License

This repository is private and maintained by BorgworX. For access, usage, or licensing inquiries, please contact [Jeff Cash](https://github.com/jlcash61).

---

# 🔄 Version

**Current Version:** v1.1

See `version_notes.md` for full changelog.

