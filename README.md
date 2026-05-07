# Cowork Plugin: My Extension

This repository contains a custom plugin designed for Microsoft Cowork / MCP (Model Context Protocol).  
It extends Copilot with additional capabilities through custom skills that can be loaded directly into your workspace.

---

## ?? Overview

This extension provides:
- A structured manifest for MCP integration
- Custom skills for contract analysis and experimentation
- Icons for UI representation (color + outline)
- A clean, modular folder structure for future expansion

---

## ?? Project Structure

my-extension/
¦
+-- manifest.json               # Plugin manifest (entry point)
+-- color.png                   # App icon (filled)
+-- outline.png                 # App icon (outline)
¦
+-- skills/                     # MCP skills
¦   +-- contract-analysis/
¦   ¦   +-- SKILL.md
¦   ¦   +-- references/
¦   ¦       +-- clause-taxanomy.md
¦   ¦       +-- risk-scoring.md
¦   ¦
¦   +-- skill-two/
¦       +-- SKILL.md
¦
+-- .vscode/                    # Editor settings (optional)

---

## ?? Getting Started

### 1. Clone the repository
git clone https://github.com/isuruvh/cowork-plugin-creation.git

### 2. Open the project
code cowork-plugin-creation

### 3. Review and update manifest.json
Ensure the manifest fields match your MCP environment requirements.

### 4. Load the plugin
Load this extension into Cowork or any MCP-compatible agent to activate the skills.

---

## ?? Skills Included

### **Contract Analysis**
Located in:
skills/contract-analysis/

Includes:
- Clause taxonomy reference  
- Risk scoring reference  
- Skill definition in SKILL.md  

This skill is designed to support legal document analysis workflows.

---

### **Skill Two**
A placeholder skill for experimentation and future development.

---

## ?? Development Notes

- All skills follow the MCP skill specification.
- Icons are included for UI integration.
- .gitignore is configured to keep the repo clean.

---

## ?? License

This project is licensed under the MIT License.
