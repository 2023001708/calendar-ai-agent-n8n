# 📅 Calendar AI Agent using n8n

## 🔹 Project Overview
This project implements a **Calendar AI Agent using n8n** that allows users to **block time slots in Google Calendar using natural language chat messages**.  
The workflow listens to chat input, understands the intent, creates a calendar event, and confirms the booking via chat.

---

## 🔹 Problem Statement
Create a Calendar AI Agent using n8n that:

- Uses a **Chat node as the trigger**
- Understands **natural language inputs**
- Integrates with **Google Calendar** to block time slots
- Confirms the booking with the user via chat

---

## 🔹 Solution Description
The workflow operates in the following steps:

1. **Chat Trigger**
   - Receives user messages such as:  
     `“Schedule a meeting tomorrow from 3 PM to 4 PM”`

2. **AI Message Processing**
   - Interprets the natural language input
   - Extracts:
     - Event title
     - Date
     - Start time
     - End time

3. **Google Calendar Integration**
   - Creates an event in Google Calendar
   - Blocks the requested time slot

4. **Chat Confirmation**
   - Confirms successful booking to the user via chat

---

## 🔹 Workflow Nodes Used
- **When Chat Message Received** (Trigger)
- **Message a Model (n8n AI / OpenAI)**
- **Google Calendar – Create Event**
- *(Optional)* Chat confirmation node

---

## 🔹 Sample Inputs
- `Block my calendar tomorrow at 2 PM`
- `Schedule a meeting tomorrow from 3 PM to 4 PM`
- `Create an event today from 10 AM to 11 AM`

---

## 🔹 Live Workflow Link
🔗 **n8n Workflow URL:**  
https://mirai.app.n8n.cloud/workflow/3hikJjga0I-gVIGzC3w_

---

## 🔹 Tools & Technologies
- n8n (Workflow Automation)
- OpenAI / n8n AI
- Google Calendar API
- Chat Trigger

---

## 🔹 Outcome
- Events are automatically created in Google Calendar
- Users interact using simple chat messages
- Demonstrates AI-powered workflow automation

---

## 🔹 Conclusion
This project shows how **AI + automation** can simplify calendar management by enabling users to schedule events naturally through chat while automating backend operations using n8n.

---

