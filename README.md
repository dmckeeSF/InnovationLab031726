# 🗽 NYC Partner Innovation Lab: Agentforce Vibes Workshop

Welcome to the **Agentforce Vibes** hands-on session! This repository is your "Zero-Config" workspace, purpose-built to get you coding immediately without the friction of local installations.

### 🎯 Why are we using this?
The purpose of this GitHub Codespace is to provide a standardized environment. It bypasses the need to manually configure Java, the Salesforce CLI, or VS Code extensions on your own machine. 

---

## 🚀 Quick Start: Launch Your Environment

To begin the workshop, click the button below. This will spin up a cloud-hosted VS Code instance with all dependencies pre-installed.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/dmckeeSF/InnovationLab031726)

> **Pro Tip:** On your first launch, it may take 1–2 minutes to initialize. Once the editor opens, look for the **Salesforce** and **Agentforce** icons in the activity bar on the left.

---

## 🛠️ Workshop Exercise: Building Unit Tests for Agentic Actions

During this lab, we are transitioning from **Agent Studio** to the **IDE** to ensure our agent's actions are robust and production-ready.

**The Goal:** Build a comprehensive Apex Test Class for the **Invokable Apex** class we just built in Agent Studio.

1.  **Authenticate:** Open the terminal in this window and run:
    `sf org login web`
2.  **Pull Metadata:** Use the Cloud icon (Salesforce Extension) to retrieve the Invokable Apex class you created in your org.
3.  **Generate with Vibes:** Open your Apex class, highlight the code, and use **Agentforce Vibes** (Cmd+Shift+I or the "Vibes" icon in the panel) to generate your test.
    * *Try this prompt:* "Write a unit test for this Invokable method. Include a test case for a single record and a bulk test case with 200 records."
4.  **Verify & Run:** Save your new test class and run it directly from the editor to see your coverage!

---

## 📚 Post-Workshop: Take Vibes Home

To continue using Agentforce Vibes in your own local environment after today, follow these official setup guides:

* **[Agentforce Vibes Local Setup](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-setup.html):** Requirements for VS Code and system dependencies.
* **[Agentforce Quick Start Guide](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-quick-start.html):** Get up and running in under 5 minutes.
* **[Troubleshooting Guide](https://developer.salesforce.com/docs/platform/einstein-for-devs/guide/einstein-troubleshoot.html):** Common fixes for connection or extension issues.

---

### 💡 Lab Reminders
* **Status Check:** If the Agentforce Vibes icon in the bottom status bar is **brown**, it is disabled. Click it to enable.
* **Telemetry:** Telemetry is **Enabled** in this container to allow the extension to communicate with the Salesforce AI services