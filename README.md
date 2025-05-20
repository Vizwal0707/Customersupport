# Customersupport
# 💬 Customer Support Chatbot - Voiceflow x Airtable

## 🧠 Overview
This project is a **customer support chatbot** built using **Voiceflow** that intelligently answers user queries using data from your website. If an answer isn't found in the knowledge base, the chatbot collects the customer's **name** and **email address** and sends it to **Airtable**, where a **live representative** can follow up.

🎯 **Try the Live Prototype:**  
[👉 Click to view chatbot](https://creator.voiceflow.com/prototype/68285e4409bde9328a5fcab8)

---

## 🚀 Features

- ✅ Answers customer queries using website knowledge base.
- ❌ If answer not found:
  - 📥 Collects user's name & email.
  - 📊 Adds data to **Airtable spreadsheet**.
  - 👤 Human representative gets notified for follow-up.
- 📅 Embedded **Calendly iFrame** for easy appointment scheduling.
- 🔄 Dynamic flow handling using **Voiceflow Variables**.
- 🔐 Safe and structured data handling.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Voiceflow** | Conversational design and chatbot logic |
| **Airtable** | Storing unanswered queries and user details |
| **Calendly** | Allowing users to schedule meetings |
| **HTML iframe** | Embedding Calendly inside the chatbot |

---

## 🧩 How It Works

1. User enters a question in the chatbot.
2. Voiceflow performs a **Knowledge Base Search** using website data.
3. If a match is found → chatbot responds directly.
4. If **no match is found**:
    - Asks the user for their **name** and **email**.
    - Adds the info to **Airtable** with the query.
    - Shows message: *"A representative will contact you soon!"*
5. Optionally, user can **book a meeting** using the Calendly iframe:
    ```html
    <iframe width="100%" height="500" frameborder="0" style="border:0"
    title="Select a Date & Time - Calendly"
    src="{{URL}}"
    allowfullscreen></iframe>
    ```

---

## 📥 Data Stored in Airtable

| Name | Email | User Query | Timestamp |
|------|-------|------------|-----------|

Live representatives can view, filter, and act on this data.

---

## 📌 Use Case Examples

- Website customer support without hiring 24/7 agents.
- Lead collection for SaaS platforms.
- Booking consultation calls directly from the bot.

---

## 👨‍💻 Author
**Vizwal Rathod Myla**  
Aspiring AI/ML Scientist | Conversational AI Enthusiast  
📬 [vizwalrathod29.myla@gmail.com](mailto:vizwalrathod29.myla@gmail.com)

---


