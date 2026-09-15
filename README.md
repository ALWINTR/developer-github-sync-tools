# ⚡ Developer GitHub Chat Synchronization & Repository Automation

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-00f0ff?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ALWINTR/developer-github-sync-tools)
[![Developer](https://img.shields.io/badge/Developer-Alwin_T_R-0284c7?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alwintr)
[![Platform](https://img.shields.io/badge/Platform-Python_3_&_GitHub_CLI-38bdf8?style=for-the-badge&logo=espressif&logoColor=white)](https://github.com/ALWINTR)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

Automated developer chat log and pair-programming repository synchronization toolchain for GitHub.

---

## 📌 Overview

An automated continuous synchronization engine built with Python and the GitHub CLI (`gh`), designed to parse developer conversation histories, scrub internal system tokens, generate structured Markdown documentation with chronological tables of contents, and automatically push sessions as public or private GitHub repositories.

---

## 🚀 Key Capabilities

- **Automated JSONL Parsing**: Reads multi-step conversation transcripts and extracts developer requests, assistant responses, and automated actions.
- **Privacy & Token Scrubbing**: Eliminates system tags, internal metadata, and local filesystem directories.
- **Automated Repository Provisioning**: Creates and synchronizes dedicated GitHub repositories via `gh repo create` and `git push`.
- **Scheduled Background Service**: Integrates with Windows Scheduled Tasks for silent 15-minute background synchronization.

---

## 👨‍💻 Author

**Alwin T R** — Robotics & Automation Engineer  
- 💼 LinkedIn: [linkedin.com/in/alwintr](https://www.linkedin.com/in/alwintr)  
- 🌌 Portfolio: [alwintr.github.io](https://alwintr.github.io)  
- 💻 GitHub: [github.com/ALWINTR](https://github.com/ALWINTR)

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
