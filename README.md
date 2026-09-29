# 🚀 AI-Powered Job Application Tracker & Automation Pipeline

An automated, end-to-end job application tracking system built with **Make (Integromat)**, **OpenAI (GPT-5)**, **Gmail**, **Google Sheets**, and **Telegram Bot**.

---

## 📌 Architecture & Data Flow

1. **Gmail:** Triggers when a new job vacancy email arrives.
2. **OpenAI:** Parses the job description against candidate skills, calculates match score (%), extracts missing skills, and returns structured JSON.
3. **Parse JSON:** Converts raw JSON string into usable scenario variables.
4. **Google Sheets:** Logs all parsed attributes into a database dashboard.
5. **Telegram Bot:** Sends real-time notification alerts directly to mobile devices.

---

## 🛠️ Tech Stack

- **Automation Platform:** Make (formerly Integromat)
- **Email Parser:** Gmail API
- **AI Processing:** OpenAI API (GPT models)
- **Data Store:** Google Sheets API
- **Alerts:** Telegram Bot API

---

## 📁 Repository Structure

```text
.
├── blueprint.json            # Exported Make scenario blueprint
├── README.md                 # Project documentation
└── assets/                   # Screenshots & workflow visuals
