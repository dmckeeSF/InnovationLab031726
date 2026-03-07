# 🗽 NYC Partner Innovation Lab: Agentforce Vibes Workshop

Welcome to the **Agentforce Vibes** hands-on session! This repository is your "Zero-Config" workspace designed to get you coding immediately. 

The purpose of this GitHub Codespace configuration is to bypass the manual setup of Java, Salesforce CLI, and VS Code extensions. Everything you need is pre-installed and ready to go in the cloud.

---

## 🚀 Quick Start: Launch Your Environment

To begin the workshop, click the button below. This will spin up a dedicated VS Code instance in your browser with all dependencies (Java 17, SFDX CLI, and Agentforce Vibes) pre-configured.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/YOUR-GITHUB-USERNAME/YOUR-REPO-NAME)

> **Note:** It may take 1–2 minutes for the container to build and the extensions to activate on your first launch.

---

## 🛠️ Workshop Exercise: Testing Agentic Actions

In this lab, we are moving from **Agent Studio** to the **IDE**. 

**The Goal:** Build a robust Apex Test Class for the `Invokable Apex` class we just created in Agent Studio. 

1. **Connect to your Org:** Open the terminal in this window and run:
   `sf org login web`
2. **Retrieve your Code:** Use the Cloud icon (Salesforce Extension) to pull your Invokable class from the org into this workspace.
3. **Generate with Vibes:** Open your class file, highlight the code, and use **Agentforce Vibes** (Cmd+Shift+I or the "Vibes" icon) to generate a unit test. 
   * *Prompt Suggestion:* "Generate an Apex unit test for this class covering positive and negative bulk scenarios."

---

## 📚 Post-Workshop: Take Vibes Home

Want to use these AI capabilities in your own local environment? Follow these guides to set up your personal machine:

* **[Agentforce Vibes Local Setup Guide](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-setup.html):** A step-by-step checklist for VS Code and CLI requirements.
* **[Agentforce Quick Start Guide](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-quick-start.html):** How to authenticate and start your first AI-assisted coding session.
* **[Safe Commands Documentation](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-safe-commands.html):** Learn how to authorize Agentforce to run CLI commands for you securely.

---

### 💡 Tips for the Lab
* **Status Bar:** Look for the **Agentforce Vibes icon** in the bottom right status bar. If it's brown, Vibes is disabled; click it to enable.
* **Telemetry:** For this cloud environment, telemetry is **Enabled** by default to allow the Agentforce Vibes extension to communicate with the Salesforce LLM.

**Happy Coding at the NYC Innovation Lab!**
