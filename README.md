# 🎓 AI-Powered Smart Education Automation System

An end-to-end AI-driven automation system designed to simplify school operations by generating exam papers and sending daily student updates to parents.

---

## 🚀 Overview

This project automates two major educational workflows:

1. 📝 **Exam Paper Generation**
2. 📩 **Daily Parent Updates**

Built using **n8n workflows**, **APIs**, and **Generative AI**, the system reduces manual effort and improves efficiency in educational institutions.

---

## 🧠 Key Features

### 📝 Exam Paper Generation
- Generates question papers automatically based on:
  - Board, Class, Subject, Chapter
  - Marks distribution and syllabus
- Uses **Generative AI (Gemini API)** to create structured questions
- Converts output into **formatted Word documents**
- Sends generated papers via **email**

---

### 📩 Daily Parent Updates
- Runs automatically every day (scheduled workflow)
- Collects:
  - Attendance
  - Homework
  - Recent grades
- Generates **personalized messages using AI**
- Sends updates via:
  - 📱 WhatsApp API
  - 📧 Email (fallback)

---

## ⚙️ Tech Stack

- **Workflow Automation**: n8n  
- **Programming**: JavaScript  
- **AI Integration**: Gemini API (Generative AI)  
- **Database**: Google Sheets  
- **Communication**: WhatsApp API, Email (SMTP)  
- **APIs**: REST APIs  

---

## 🏗️ System Architecture

1. Trigger (Google Sheets / Scheduler)
2. Data Fetch (Student / Syllabus / Marks)
3. Processing (Validation + Transformation)
4. AI Generation (Questions / Messages)
5. Output:
   - Word Document (Exam Paper)
   - WhatsApp / Email (Updates)
6. Logging & Monitoring

---

## 🔄 Workflow Highlights

- 🔁 Fully automated pipelines using n8n
- ✅ Data validation and error handling
- 📊 Logging of all operations
- 🔄 Fallback system (Email if WhatsApp fails)
- 📈 Scalable for multiple students, classes, and boards

---

## 📸 Sample Outputs

### 📄 Exam Paper
- Auto-generated structured question paper
- Proper sections and marks distribution

### 💬 Parent Message
- Attendance status (Present/Absent)
- Homework updates
- Recent performance summary

---

## 🧩 Challenges Solved

- Structured AI response handling
- Dynamic marks distribution calculation
- Multi-source data integration
- Reliable message delivery with fallback mechanism

---

## 🚀 Future Enhancements

- Dashboard using Power BI
- Mobile app integration
- Real-time notifications
- AI-based performance analytics

---

## 📌 How It Works

1. Input data is provided via Google Sheets or triggers
2. Workflow processes and validates data
3. AI generates content based on structured prompts
4. Output is formatted and delivered automatically

---

## 👨‍💻 Author

**Chitturi Durga Satya Sai Kiran**  
- GitHub: https://github.com/Keyrun1227  
- LinkedIn: https://linkedin.com/in/durga-satya-sai-kiran-chitturi-69abba220  

---

## ⭐ Final Note

This project demonstrates real-world usage of **AI + Automation + APIs** to solve practical problems in education.

If you found this useful, feel free to ⭐ the repo!
