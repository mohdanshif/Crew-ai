# 🧠 Crew AI Blog Automation & HTML Webpage Generator

This project uses [CrewAI](https://github.com/joaomdmoura/crewAI) to **automatically plan, write, edit, and design** a blog post as a styled HTML page, starting only from a topic.

It demonstrates:
- Multi-agent collaboration (Planner, Writer, Editor, Web Developer)
- Integrating external tools (e.g., Google Images search via SerpAPI)
- Generating colorful, attractive HTML pages dynamically

---

## ⚙️ Usage of AI

This project leverages AI to fully automate the process of writing and publishing blog content, starting from a single topic. Here’s what each AI agent does:

✅ **Content Planner:**  
- Researches the topic, finds trends and key points  
- Identifies target audience & SEO keywords  
- Creates a detailed content outline

✅ **Content Writer:**  
- Expands the outline into a complete, engaging blog post  
- Adds sections, introduction, and conclusion  
- Writes in a style that's informative yet opinionated

✅ **Editor:**  
- Proofreads for grammar and clarity  
- Ensures tone matches brand style  
- Balances opinions and facts

✅ **Web Developer:**  
- Searches for relevant images (via SerpAPI)  
- Designs a colorful HTML page with CSS/JS styling  
- Embeds text and images into a single HTML file

With this setup, the AI saves hours of manual effort and produces:
- SEO-friendly blog content
- Professional editing
- A ready-to-publish HTML webpage

---

## 📦 Installation

Install required packages:

```bash
!pip install crewai==0.86.0
!pip install crewai-tools==0.25.0
!pip install langchain_community==0.0.29
!pip install serpapi==0.1.5
