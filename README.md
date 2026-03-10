# ai-agents-portfolio

# OSINT News Intelligence Agent

An AI-powered news analysis agent built with n8n and Claude API.
No code written — built entirely with visual workflow tools.

## What It Does
Automatically pulls the latest AI regulation news, analyzes each article 
and classifies it by source legitimacy, regulatory stance, and sentiment.

## Workflow Diagram
![Workflow](osintworkflow.png)

## Sample Output
![Output](osintoutput.png)

## Tools Used
- n8n (workflow automation)
- NewsAPI (news data)
- Claude API (AI analysis)
- Google Sheets (output)

## Fields Classified Per Article
- Source Legitimacy: HIGH / MEDIUM / LOW
- Regulatory Stance: PRO-REGULATION / ANTI-REGULATION / NEUTRAL
- Sentiment: POSITIVE / NEGATIVE / NEUTRAL
- Stance Reason
- Summary
