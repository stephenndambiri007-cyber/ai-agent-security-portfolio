# AI Agent Security Portfolio

## About Me
I am an AI Security Red Teamer specializing in identifying vulnerabilities in autonomous agents and LLM-powered workflows. This repository documents my hands-on experience exploiting and mitigating security flaws in agentic environments.

## Repository Contents

### 1. Arkx CTF Writeups
This folder contains detailed writeups from the Arkx Agent Security CTF. I successfully exploited 6 advanced/expert levels, capturing flags by bypassing agentic safety controls.
*   **Vulnerability Classes Explored:** Code Injection, Insecure Deserialization, API Authorization Bypass, Session Forgery, Race Conditions, and Out-of-Band Data Exfiltration.
*   **Key Takeaway:** Learned how to bypass LLM guardrails and exploit underlying backend logic.

### 2. AgenticVerse Task Development
This folder contains original YAML scenarios I authored for the AgenticVerse evaluation platform. These tasks are designed to test whether AI agents can be tricked into performing policy-violating actions (Indirect Prompt Injection).
*   **Task Focus:** Enterprise tool-use (GitHub, Salesforce).
*   **Evaluation:** Each task is tested against state-of-the-art models to ensure it meets the required Attack Success Rate (ASR).

## Skills Demonstrated
*   **Offensive:** Prompt Injection (Direct & Indirect), YAML Deserialization, OS Command Injection, MCP API Exploitation, TOCTOU Race Conditions.
*   **Defensive:** Secure code review, input sanitization, safe deserialization (yaml.safe_load), API authorization enforcement.
*   **Tools:** Burp Suite, curl, Python, Windows Command Prompt, AgenticVerse, Arkx.
