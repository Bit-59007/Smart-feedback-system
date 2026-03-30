# Smart Feedback System

An automated feedback management system that collects user submissions, processes responses, categorizes feedback, stores it in a database, and notifies both customers and relevant teams using workflow automation.

---

## 🚀 Features

- Collect user feedback through a form  
- Automatically process and categorize responses (e.g., Complaints, Suggestions, Compliments)  
- Store feedback data in a structured database (Airtable)  
- Route feedback to relevant teams or departments using Slack  
- Send automated notifications:
  - Customer confirmation message  
  - Admin/Owner alerts  
- Real-time workflow automation using n8n  
- Scalable and easy to extend  

---



## 🛠️ Workflow Nodes Used

- Webhook Node (to receive form submissions)  
- Merge Node (to combine data streams)  
- Set Node (to structure and format data)  
- IF Node (to categorize feedback based on conditions)  
- Airtable Node (to create and manage records)
- Gmail Node

---

## ⚙️ How It Works

1. User submits feedback through a form  
2. Data is sent to a webhook (n8n workflow)  
3. Workflow processes the input  
4. Feedback is categorized (Complaint, Suggestion, etc.)  
5. A record is created in the database  
6. Notifications are sent:
   - To the customer (confirmation)  
   - To the admin/owner  
   - To the relevant team  
7. Data is stored for future use  

---

## 🔄 Workflow Overview

Form Submission → Webhook Trigger → Data Processing → Categorization → Database Storage → Notifications  

---

## 📊 Use Cases

- Customer feedback systems  
- Complaint management  
- Support ticket routing  
- Survey automation  
- Internal communication workflows  

---

## 📌 Future Improvements

- AI-based sentiment analysis  
- Analytics dashboard  
- Email/SMS notifications  
- User authentication system  
- Advanced filtering and reporting  

---

## 📷 Screenshots
<img width="1523" height="683" alt="image" src="https://github.com/user-attachments/assets/b5a7f7b3-391e-44fb-bf54-c8f076e6005b" />


## 🤝 Contributing

Contributions are welcome! Fork this repository and submit a pull request.

---

