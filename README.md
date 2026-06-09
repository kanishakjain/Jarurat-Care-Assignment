# 🏥 Jarurat Care

> A mini healthcare support web app built for NGO use — helping patients, volunteers, and the community connect through a single platform.

---

## 🌐 Live Demo

[View Live Site](https://jarurat-care-assignment1.vercel.app)

---

## 📌 NGO Use Case

Jarurat Care is designed for grassroots healthcare NGOs in India. It solves three core problems in one place — patients can request help, volunteers can register their skills, and anyone can reach out for partnerships or queries. The AI triage feature helps NGO staff prioritize which patients need urgent attention without needing a doctor to manually review every submission.

---

## ✨ Features

- 🩺 **Patient Support Form** — collects name, age, phone, language preference, and symptom description
- 🤝 **Volunteer Registration Form** — collects skills, availability, city, and contact details
- ✉️ **Contact Form** — for general inquiries and partnership requests
- 🔍 **AI Smart Triage** — analyses patient symptoms using Gemini AI and assigns a priority tag (🔴 Critical / 🟡 Moderate / 🟢 Low) with a recommended next step
- 💾 **Supabase Integration** — all form submissions are saved to a database in real time

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, Vanilla JavaScript |
| AI / Triage | Google Gemini 2.5 Flash API |
| Database | Supabase (PostgreSQL) |
| Hosting | Vercel |

---

## 🤖 AI Idea — Smart Triage

When a patient submits their symptom description, the app sends it to **Gemini 2.5 Flash** with a structured prompt. The model classifies urgency as `CRITICAL`, `MODERATE`, or `LOW` and returns a short recommended next step. This helps NGO staff quickly identify who needs immediate medical attention — without any manual review.

---

## 🗄️ Database Tables

- `patient_requests` — stores all patient form submissions including triage result
- `volunteer_registrations` — stores volunteer details and availability
- `contact_messages` — stores contact form submissions

---

## 🚀 Setup

1. Clone or download this repo
2. Open `index.html`
3. Replace `YOUR_GEMINI_API_KEY` with your Gemini API key
4. That's it — no npm, no build step needed

---

## 📁 Project Structure

```
jarurat-care/
└── index.html   
```

---

*Built with care for community health 🇮🇳*
