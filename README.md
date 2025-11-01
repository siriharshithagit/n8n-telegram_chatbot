# 📧 Automated Email Sender using n8n + Google Sheets + Schedule Trigger

This project automates the process of sending emails to multiple recipients based on data stored in **Google Sheets**.  
The workflow uses **n8n** to read each row from the sheet and sends an email to the respective person **automatically at a scheduled time**.

---

## 🧠 Problem Statement
Sending emails manually to many people is time-consuming and often leads to delays or missed communication.  
There is a need for a **simple automated system** that reads recipient details from a spreadsheet and sends emails automatically on time.

---

## 🎯 Objective
- Store recipient email details and message content in Google Sheets.
- Automatically send emails using a schedule trigger.
- Ensure timely and consistent communication without manual effort.

---

## 🛠️ Tools & Technologies Used

| Tool / Service | Purpose |
|----------------|---------|
| **n8n** | Automation workflow platform |
| **Google Sheets** | Stores recipient emails and message details |
| **Schedule Trigger (Cron)** | Runs workflow at the specified time |
| **Email / Gmail Node** | Sends emails to the recipients |

---

## 🧱 Google Sheets Structure

Example format:

| Name | Email Address | Message | Send Time |
|------|---------------|---------|-----------|
| Rahul | rahul@gmail.com | Meeting today at 4 PM | 10:00 |
| Sneha | sneha@gmail.com | Submit assignment today | 10:00 |

You can update or add new rows anytime — no workflow changes required.

---

## 🔁 Workflow Overview


<img width="1826" height="815" alt="image" src="https://github.com/user-attachments/assets/fc7a63c4-6102-4270-9de9-d92eb395a885" />



<img width="570" height="123" alt="image" src="https://github.com/user-attachments/assets/8e045f7c-0fd0-4665-9e91-f0d0103c217e" />


![WhatsApp Image 2025-11-01 at 14 19 02_7f7f4671](https://github.com/user-attachments/assets/ef245c84-3be5-40f9-97e9-22d5061ed3da)

### ✅ Advantages
- Fully automated email sending
- Easy to maintain (just edit Google Sheet)
- No coding required
- Works for unlimited recipients
- Ensures timely communication

---

### 🔮 Future Scope
- Send reminders before deadlines
- Send scheduled WhatsApp or SMS alerts
- Add conditions (e.g., send only if Send Time matches current time)
- Log sent emails into another sheet

---

## ▶️ How to Use

1. Create a Google Sheet with the required columns.
2. Connect Google Sheets and Email credentials in n8n.
3. Import the workflow file:
4. Set the **Schedule Trigger** time (e.g., daily at 10 AM).
5. Activate the workflow — emails will send automatically 📨

---
##PPT Link
https://docs.google.com/presentation/d/1Rg4c9tpFSLCdx3rYKBndUqs4TFNw6MEJ/edit?usp=drivesdk&ouid=115803794330173249605&rtpof=true&sd=true
