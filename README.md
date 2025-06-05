# 📘 Kujia Jobs Mtandao – MVP Development Plan

**Prepared by:** Product Manager (Tiff)
**Date:** 5th June 2025
**Timeline:** 14 Weeks (June–September 2025)
**Objective:** Deliver a functional, secure, and youth-friendly job platform connecting Kenyan youth (ages 18–35) with tech employment opportunities.

---

## 🎯 Project Goals & Vision

* Build an intuitive platform for **youth** to showcase ICT skills and apply for jobs.
* Enable **employers** to post jobs, vet candidates, and contribute via placement fees or donations.
* Ensure the platform is **scalable, secure, and socially impactful**.

---

## 👨‍💻 Development Teams & Responsibilities

Based on skills, preferences, and availability, developers have been assigned to the following sub-teams:

### 🧩 Frontend Team

**Goal:** Build a responsive, WCAG-AA compliant UI using React.js.

| Name             | Key Skills                   | Availability          | Notes                      |
| ---------------- | ---------------------------- | --------------------- | -------------------------- |
| Eliot Owiti      | React.js, JavaScript, Docker | 10 hrs/week           | Design implementation lead |
| Margaret Muthoni | HTML, CSS, React.js          | 8 hrs/week (Evenings) | Support UI components      |
| Nolin Masai      | Python, Frontend interest    | 10 hrs/week           | AI integration support     |

**Key Tasks:**

* Build youth and employer dashboards
* Develop job posting forms and profile components
* Integrate with backend APIs
* Implement responsive design & accessibility

---

### 🛠️ Backend Team

**Goal:** Implement server logic using Node.js/Express (or Django), connect to PostgreSQL, and integrate payment systems.

| Name             | Key Skills              | Availability | Notes                    |
| ---------------- | ----------------------- | ------------ | ------------------------ |
| Agustine Nyaanga | Node.js, Firebase, APIs | 30 hrs/week  | Backend lead             |
| Eliot Owiti      | Docker                  | 10 hrs/week  | Supports DevOps pipeline |

**Key Tasks:**

* Set up authentication (OTP/email)
* Role-based access control
* CRUD for jobs, users, and profiles
* Integrate M-Pesa, Stripe, Flutterwave APIs
* Secure admin controls and MOU logic

---

### 🤖 AI Team

**Goal:** Enhance profile-job matching & integrate analytics insights.

| Name         | Key Skills           | Availability      | Notes                      |
| ------------ | -------------------- | ----------------- | -------------------------- |
| Nolin Masai  | AI/ML, Flask, SQL    | 10 hrs/week       | AI module lead             |
| Mercy Otieno | AI concepts, Copilot | Weekends/evenings | Data preprocessing support |

**Key Tasks:**

* Build domain-based job recommendation engine
* Tag and score youth profiles for employer filters
* Assist in future predictive analytics for hiring trends

---

## 🗓️ Development Schedule

| Week(s) | Phase         | Objectives                                 | Milestones                                                          |
| ------- | ------------- | ------------------------------------------ | ------------------------------------------------------------------- |
| 1       | Planning      | Finalize scope, assign roles, set up tools | Team kickoff, repo & task board setup                               |
| 2–3     | Design        | Wireframes & branding                      | UI mockups approved                                                 |
| 4–9     | Development   | Full-stack implementation                  | ✅ Login/Auth <br> ✅ Job posting <br> ✅ Profile mgmt <br> ✅ AI logic |
| 10–11   | Testing & QA  | Manual & automated tests, bug fixing       | Bug-free MVP, 90% test coverage                                     |
| 12      | Soft Launch   | Internal user testing, employer feedback   | Feedback doc & patch fixes                                          |
| 13      | Public Launch | Release to public                          | Platform live                                                       |
| 14      | Wrap-up       | Reports, handover docs, future planning    | Final report & sprint retrospective                                 |

---

## 🎯 Milestones Summary

* **Week 3:** Wireframes & UI prototype
* **Week 6:** Core backend endpoints & frontend views complete
* **Week 9:** All modules integrated (auth, job board, AI)
* **Week 11:** Platform is stable, secure & test-passed
* **Week 13:** Official Launch

---

## 📬 Communication & Tools

* **Daily Standups:** Async check-in via WhatsApp group
* **Weekly Syncs:** Sundays at 7PM (Google Meet)
* **Code Repo:** GitHub (Agustine to set up)
* **Project Board:** Trello/Notion (Product Manager to manage)
* **Channels:**

  * WhatsApp (urgent comms)
  * Slack (discussions, files)
  * Google Meet (video calls)
  * Email (documentation)

---

## ✅ Objectives Recap

* 🎯 Deliver a functional MVP in 14 weeks
* 🔒 Ensure user security, GDPR compliance, and role-based access
* 💼 Implement an employer hiring workflow with payment
* 🧠 Integrate AI logic for profile-job matching
* 🔍 Ensure scalability for future growth (10,000+ users)

---

## 📝 Notes & Recommendations

* Prioritize **mobile optimization** – youth will access the platform via mobile.
* Use **test-driven development (TDD)** wherever possible.
* Ensure **version control discipline** and code reviews before merges.
* Collect **user feedback** during soft launch for final tweaks.
* Consider setting up **future CI/CD pipelines**.

---

Please confirm the plan, and I’ll share individual task lists, GitHub repo structure, and the Trello board setup next.
