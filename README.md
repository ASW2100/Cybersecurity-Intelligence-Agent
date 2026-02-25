# Cybersecurity-Intelligence-Agent

## Overview

This repository contains a multi-agent AI system that automates cybersecurity threat analysis by leveraging:
- CrewAI for orchestrating AI agents
- LangChain-Groq (Llama 3-70B) for AI-powered reasoning
- EXA API for real-time cybersecurity intelligence search


## Key Features
- **Threat Intelligence Gathering** – Fetches the latest malware trends and cyberattacks
- **Vulnerability Research** – Identifies and analyzes new CVEs (Common Vulnerabilities and Exposures)
- **Incident Response Advisor** – Recommends mitigation strategies for detected threats
- **AI-Generated Cybersecurity Reports** – Summarizes all findings into a structured Threat Intelligence Report

## How It Works
1. **Threat Analyst Agent** – Uses EXA API to fetch the latest cybersecurity threats
2. **Vulnerability Researcher Agent** – Retrieves new software vulnerabilities and security flaws
3. **Incident Response Advisor Agent** – Provides remediation strategies for identified threats
4. **Cybersecurity Report Writer Agent** – Generates a structured cybersecurity report

## Tech Stack
- Python
- CrewAI
- LangChain-Groq (Llama 3-70B)
- EXA API

## Uses
- **SOC Teams** – Automate threat intelligence gathering
- **Cybersecurity Researchers** – Generate structured vulnerability reports
- **Enterprises** – Improve incident response strategies
