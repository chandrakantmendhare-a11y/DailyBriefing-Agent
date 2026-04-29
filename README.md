# DailyBriefing-Agent

An autonomous AI agent designed to bridge the gap between daily tech trends and active skill building.

## Overview
This project uses **Agentic AI** to automate the process of staying updated in a fast-paced tech landscape. Every day, the agent autonomously researches, summarizes, and distributes high-value information to professional communication channels.

## Tech Stack
- **Orchestration:** [Gumloop] (https://gumloop.com) (Agentic Framework)
- **Reasoning Model:** Claude 3.5 Sonnet
- **Search Engine:** Firecrawl (Web Scraping & Search)
- **Communication:** Slack API
- **Data Persistence:** Google Sheets API

## Agent Logic
The agent follows a **Reasoning -> Action -> Observation** loop:
1. **Search:** Scans for top AI news in India and beginner-friendly Python tips.
2. **Filter:** Applies conditional logic to find free internship opportunities.
3. **Summarize:** Condenses complex info into student-friendly bullet points.
4. **Distribute:** Posts summarizes to Stack for immediate reading.
5. **Archive:** Appends data to a Google Sheet 'Knowledge Vault' for long-term tracking.

## Learning Impact
By automating the "discovery" phase of learning, I focus my on the "application" phase-building projects based on the tips discovered by this agent.
By
