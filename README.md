# 🤖 ATS System - AI Agent (Relevance AI)

> An AI-powered Applicant Tracking System that matches LinkedIn profiles with Job Descriptions and gives a percentage match score + profile summary.

\---

## 📌 What is this?

This is my **first AI Agent project** built using **Relevance AI**. It works like an ATS (Applicant Tracking System) — the same technology companies use to screen candidates — but powered by AI and accessible to anyone.

\---

## 🚀 How it Works

```
LinkedIn Profile URL + Job Description
            ↓
    RapidAPI fetches LinkedIn data
            ↓
    LLM parses and analyzes profile
            ↓
  ✅ Match % Score + Profile Summary
```

\---

## 🎯 Features

* 🔗 **LinkedIn Profile Scraping** — Just paste the profile URL
* 📋 **Job Description Analysis** — Paste JD up to 300 words
* 📊 **Match Percentage** — Know how well the profile fits the role
* 📝 **Profile Summary** — Clean AI-generated summary of the candidate
* ⚡ **Instant Results** — Powered by LLM for fast analysis

\---

## 🛠️ Tech Stack

|Tool|Purpose|
|-|-|
|**Relevance AI**|Agent builder platform|
|**RapidAPI**|LinkedIn profile data fetching|
|**LLM**|Profile parsing \& analysis|

\---

## 📸 Screenshots

### Agent Flow

!\[ATS Agent Flow](screenshots/agent-flow.png)

### Input Form

!\[Input Form](screenshots/input-form.png)

\---

## ▶️ How to Use

1. Open the tool using the link below
2. Enter a **LinkedIn Profile URL** in the format:

```
   https://www.linkedin.com/in/XXXXXXXXX
   ```

3. Enter the **Job Role \& Responsibilities** (up to 300 words)
4. Click **Compare**
5. Get your **Match % and Profile Summary** instantly!

\---

## 🔗 Live Tool

👉 [Try the ATS System here](https://app.relevanceai.com/form/bcbe5a/bd40cea7-0c75-480f-93dd-a19b0c888160)

\---

## 💡 Use Cases

* **Recruiters** — Screen candidates quickly against JDs
* **Job Seekers** — Check how well your profile matches a job
* **HR Teams** — Automate first-round candidate screening
* **Freelancers** — Offer ATS screening as a service

\---

## 🗺️ Agent Architecture

```
┌─────────────────────────────────────┐
│              INPUTS                 │
│  • linkedin\_profileid (URL)         │
│  • job\_role (description)           │
└────────────────┬────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────┐
│     RapidAPI - LinkedIn Scraper     │
│  Fetches profile data from LinkedIn │
└────────────────┬────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────┐
│       LLM - Profile Parser          │
│  Analyzes profile vs job description│
└────────────────┬────────────────────┘
                 │
                 ▼
┌─────────────────────────────────────┐
│             OUTPUTS                 │
│  • Match Percentage (%)             │
│  • Profile Summary                  │
└─────────────────────────────────────┘
```

\---

## 📅 Version History

|Version|Date|Update|
|-|-|-|
|v1.0|May 18, 2026|Initial release - ATS System live|
|v1.1|May 19, 2026|Published \& shared on LinkedIn|

\---

## 🧠 What I Learned

* How to build AI agents using **Relevance AI**
* How to connect **RapidAPI** for LinkedIn data
* How to use **LLM prompting** for profile analysis
* How to **publish and share** an AI tool

\---

## 👤 Author

**Naga Babu Goli**

* 🐙 GitHub: [golinagababu700-gif](https://github.com/golinagababu700-gif)
* 💼 LinkedIn: https://www.linkedin.com/in/nagabob

\---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

\---

## 🌟 Support

If you found this helpful, please give it a ⭐ on GitHub!

> 💡 \*This is Project #1 in my AI Engineering journey. More agents coming soon!\*

