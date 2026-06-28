100Hires Portfolio Project — Setup Documentation

Author: Salva Feyza Najwa Zaferina
Date: June 2026
Role Applied: Junior Growth Marketing Specialist

🛠️ Tools Installed

1. Cursor IDE

- Downloaded from: [https://cursor.com/](https://cursor.com/)
- Version: 3.8.24 (Stable)
- Purpose: AI-powered code editor that enables faster development and problem-solving with built-in AI assistance

1. Claude AI (Built-in Cursor)

- No separate installation required
- Claude AI is natively integrated into Cursor as its core AI assistant, it powers the chat interface that appears on Cursor's landing page
- Purpose: AI assistant for code generation, documentation, and problem-solving within the editor

1. Codex Extension (in Cursor) — Not Found

- Attempted installation via: Extensions → search "Codex"
- Result: Extension not available in Cursor's plugin marketplace (results returned were unrelated: Monk.io, Render, Compound Engineering)
- Finding: After researching, OpenAI Codex was deprecated in 2023 and is no longer available as a standalone tool or extension
- Resolution: Cursor's built-in Claude AI serves the same purpose of AI-powered code assistance

✅ Steps Completed

1. Created a GitHub account (existing: github.com/salvaf28)
2. Downloaded and installed Cursor IDE from cursor.com
3. Opened Cursor and explored the interface
4. Confirmed Claude AI is built-in to Cursor — no separate installation needed
5. Navigated to Cursor's plugin marketplace → searched "Codex" → not found → documented findings
6. Created this public repository: 100hires-portfolio
7. Cloned repository locally and opened in Cursor
8. Created this README.md documentation file
9. Committed and pushed to GitHub



**📊 Research Project — AI-Powered SEO Content Production** 

**Why I chose this topic** 

AI-powered SEO content production sits at the intersection of my background in media production and my hands-on experience building an AI-powered system for my undergraduate thesis. I chose this topic because it represents the most significant shift in content marketing right now and because I wanted to research something I could apply immediately, not just study abstractly. 

**What I collected** 

10 high-signal experts across LinkedIn posts, articles, and newsletters, selected based on:

- Active practitioner status (runs agency, builds tools, or advises real clients)
- Documented results with real metrics 
- Cross-referenced credibility across multiple sources 
- Content published in the last 3 months (March–June 2026) 

**Expert breakdown** 

1. Jake Ward = LinkedIn — Programmatic SEO + AI content at scale 

2. Lily Ray = LinkedIn — E-E-A-T + AI search quality 

3. Kevin Indig = LinkedIn — AI search strategy + Growth 

4. Aleyda Solis = X/Newsletter — International GEO + AI search metrics

5. Mike King = Articles — Relevance Engineering + GEO

6. Ross Simmonds = LinkedIn — Content distribution + Reddit B2B

7. Eli Schwartz = LinkedIn — Product-led SEO + AEO

8. Marie Haynes = LinkedIn — Google AI updates + Agentic web

9. Koray Tugberk = LinkedIn — Semantic SEO + Topical authority

10. Julian Goldie = LinkedIn — AI SEO implementation workflows

**Repository structure** 

-  `/research/sources.md` — annotated list of all 10 experts 
-  `/research/linkedin-posts/` — posts organized by author 
- `/research/other/` — articles and newsletter content



⚠️ Issues Encountered & How I Solved Them

Issue 1: Codex Extension Not Available

- Problem: The assignment instructed me to install a "Codex add-on in Cursor." When I searched the Cursor plugin marketplace, Codex was not found — only unrelated plugins appeared.
- Solution: I researched independently and found that OpenAI Codex was officially deprecated in March 2023. It is no longer available as a standalone extension or tool. Cursor's built-in Claude AI serves the same functionality of AI-powered code completion and assistance.
- Resource used: Google search + OpenAI's official deprecation announcement.

Issue 2: Unexpected Interface — AI Chat vs File Explorer

- Problem: Based on prior experience with VS Code, I expected Cursor to have a traditional file explorer interface as its landing page. However, Cursor's default landing page is an AI chat interface, which was initially confusing during onboarding.
- Solution: I explored the interface independently and discovered that the traditional file/folder view is accessible through the sidebar after opening or cloning a repository. No external resources needed, resolved through self-directed exploration.
- Insight: This gap between user expectation and actual product experience is a classic PM problem. It highlighted how prior mental models from similar tools (VS Code) can create friction when onboarding to a new product, even when that product is objectively more powerful. This is exactly the kind of UX friction I analyzed in my thesis research when studying why MSME operators struggled to adopt conventional financial apps.

💡 Reflections

This setup process, while straightforward, reinforced several principles I've developed through my undergraduate thesis project.
First, the importance of resourceful problem-solving: when Codex was not found, I didn't stop at the error, I researched why, found the answer, and documented it clearly. Finding answers independently is a habit I built during my thesis, where I regularly had to debug deployment issues on a live VPS server, resolve API integration errors, and iterate the system based on real user feedback from field research.
Second, the value of connecting product experience to PM thinking: noticing that Cursor's interface contradicted my mental model as a VS Code user wasn't just a personal frustration, it's a data point about product onboarding design. The best PM insight often comes from paying attention to your own experience as a user.
As someone who has built and deployed a full-stack AI-powered system for my undergraduate thesis by managing cloud infrastructure, API integrations, and iterating based on qualitative user research, this onboarding process felt familiar in approach, even if the specific tools were new.
From a growth marketing perspective, this onboarding experience also reinforced how critical the first few minutes of user activation are. The friction I experienced as a new Cursor user, where my mental model didn't match the actual interface, mirrors the exact adoption barriers I documented in my thesis research on MSME technology adoption. Understanding where and why users drop off during onboarding is foundational to growth work, and this hands-on experience as a confused new user was a useful reminder of that.

📁 Related Work

As context for my technical and product background:
WhatsApp Chatbot for MSME Financial Management (Undergraduate Thesis, 2026)

- Stack: Node.js, Python Flask, Firebase Firestore, Groq API (Llama 3.3 + Vision), Vercel, DigitalOcean VPS.
- Conducted 3-week field research with 5 MSME informants by user interviews, observation, and system log analysis.
- Iterated product features based on real user behavior (e.g., discovered and implemented batch recording mode after observing actual usage patterns).
- Repository is kept private due to sensitive API credentials and WhatsApp integration configurations. The project demonstrates end-to-end product development experience including user research, iterative feature development, and field deployment.

