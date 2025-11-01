# 📅 Telegram Daily Schedule Bot using n8n & Google Calendar

This project automates the process of fetching daily schedule events from **Google Calendar** and sending them to a **Telegram Bot** using an **n8n workflow**.  
It helps users stay organized by providing instant reminders in a platform they use every day.

---

## 🚀 Problem Statement
Many students and professionals rely on digital calendars to manage their schedules. However, they often **forget to check** the calendar regularly which leads to missed classes, meetings, or deadlines.  
There is a need for a system that **automatically delivers the schedule** to a user in a convenient and frequently-used platform like **Telegram**.

---

## 🎯 Objective
- Automatically retrieve daily schedule from Google Calendar.
- Format and send the schedule message to a Telegram chat.
- Improve time management and productivity.
- Reduce manual checking and dependency on memory.

---

## 🛠️ Tools & Technologies Used

| Tool / Service | Purpose |
|----------------|---------|
| **n8n**        | Workflow automation platform to connect services. |
| **Google Calendar API** | Source of events and schedule data. |
| **Telegram Bot** | Sends formatted message to the user on Telegram. |
| **Webhook / Trigger Node** | Initiates the workflow based on user command. |

---

## 🔁 Workflow Overview

**Explanation:**
1. The user sends a trigger command in Telegram.
2. n8n receives the command through a **Webhook**.
3. Google Calendar events for the day are fetched.
4. The schedule is formatted (converted to IST + structured cleanly).
5. A Telegram Bot sends the final schedule back to the user.
<img width="1721" height="780" alt="image" src="https://github.com/user-attachments/assets/502d2a43-05a3-456e-8d33-afe12c499049" />


---

🔮 Future Scope
- Auto-send schedule daily at a fixed time (e.g., 7 AM).
- Reminders before each event.
- Weekly or monthly schedule summaries.
- Multi-user support with authentication.
- Integration with WhatsApp, Slack, Discord, etc.
- Smart priority tagging for important events.



