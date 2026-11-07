# n8n Automation Workflows

A collection of AI-powered automation workflows built during my AI Engineering mentorship at Valerix AI.

## Shopify TikTok Shop AI Agent

The main project. You message it on Telegram in plain English and it manages a live Shopify store in real time - finding trending products, calculating profit margins, and creating, updating or deleting listings automatically.

**How it works:**
- Telegram is the interface - just chat with it normally
- The AI agent decides which tools to use based on your message
- SerpAPI searches for trending products and market data
- A JavaScript node calculates profit margins and scores each product
- Shopify API handles all store operations
- Every action is logged to Google Sheets automatically
- Conversation memory means it keeps context across messages

**Stack:** n8n, OpenAI, Shopify API, SerpAPI, Telegram, Google Sheets

---

## Hacker News LinkedIn Digest

Runs on a schedule, pulls the top AI and tech stories from Hacker News, and uses OpenAI to draft LinkedIn posts from them. Results logged to Google Sheets and delivered by email.

**Stack:** n8n, OpenAI, Google Sheets, Gmail

---

## Stock Market News Digest

Pulls live stock market news from SerpAPI, processes it through an AI agent, and delivers a written summary by email on a schedule.

**Stack:** n8n, SerpAPI, OpenAI, Gmail

<img width="906" height="344" alt="image" src="https://github.com/user-attachments/assets/721ec473-89c4-40e1-a87d-df46df89039c" />
