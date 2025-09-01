# Siri + n8n Personal Assistant

Siri is good at setting alarms and reminders, but it doesn’t act like a true personal assistant.  
This project fixes that by connecting **Siri Shortcuts** with **n8n** workflows and AI.  

## ✨ Features (v1)
- 📧 **Email** → Summarizes inbox, drafts replies, and nudges important messages.  
- 📅 **Calendar** → Provides a daily agenda and helps with smart scheduling.  
- 🌐 **Web Research** → Runs searches and returns concise AI summaries.  

Instead of just listening, Siri now actually *does things*.  

## 🎥 Demo
Watch the full demo here: [[YouTube Link]](https://youtu.be/TNvFyeE1ILY)  

## ⚙️ How It Works
1. Siri Shortcuts trigger n8n webhooks.  
2. n8n workflows connect to APIs (mail, calendar, web search).  
3. AI (LLM) processes the results and sends back actionable outputs.  

## 🚀 Setup
1. Clone this repo and open in n8n.  
2. Import the workflow JSON from `/workflows`.  
3. Add your credentials (e.g., Gmail, Outlook, Google Calendar).  
4. Link the workflow to Siri Shortcuts for voice triggers.  

## 🔮 Future Plans
- Weather + contextual reminders.  
- Finance tracking and bill alerts.  
- Deeper task manager integrations.  

---

### 📂 Repo Structure
