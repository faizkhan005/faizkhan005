<div align="center">

# Hi, I'm Faizan 👋
### Backend Engineer · Offline-first systems · .NET & Python · MS Computer Engineering @ NYU Tandon

[![Portfolio](https://img.shields.io/badge/Portfolio-faizkhan005.github.io-111827?style=flat&logo=githubpages&logoColor=white)](https://faizkhan005.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/faizan-ahmed-khan-814521191)
[![Email](https://img.shields.io/badge/Email-Say%20hi-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:faizanahmedkhan005@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-PDF-22C55E?style=flat&logo=readthedocs&logoColor=white)](https://faizkhan005.github.io/assets/Faizan_Ahmed_Khan_Resume.pdf)

</div>

---

## 🧑‍💻 About Me

I spent 3 years at **Epicor** making production software work where the network doesn't. As primary and later sole developer of the **Epicor FSM** field service mobile app, I took data synchronization failures between technicians' offline devices and the server from **1 in 3 runs to nearly zero**.

I'm now pursuing an **MS in Computer Engineering at NYU Tandon** (graduating Dec 2027) and expanding into Python and machine learning systems.

- 🎓 **Now:** MS Computer Engineering, NYU Tandon · Machine Learning, Computer Architecture, Real-Time Embedded Systems
- 🏢 **Previously:** Associate Product Developer @ Epicor (Feb 2023 to Jan 2026, including internship)
- 💼 **Open to:** Summer 2027 internships and part-time roles · Backend · Forward Deployed · Applied AI
- 📍 **Based in:** New York, NY
- 🟢 **Green Card holder**, no sponsorship required

---

## 🏢 What I Shipped at Epicor

| Problem | What I did | Result |
|---|---|---|
| Sync failed on about 1 in 3 runs and silently wiped technicians' unsynced, billable work | Rebuilt the offline sync engine with batched incremental sync over 25,000+ records and conflict handling | Failures down to **nearly zero**, no more lost field work |
| Every on-device schema change forced customers to reinstall the app | Built versioned SQL migrations supporting upgrades and downgrades across up to 5 app versions | **Zero forced reinstalls** across 20+ releases |
| App crashed for technicians after about 10 minutes of use | Traced it with memory profiling to retained UI components and undisposed camera streams, and drove the fix | **Memory crashes eliminated** |
| Screens slowed down as large ERP customers came on board | OData server-side pagination, stored procedure tuning, legacy pages migrated to .NET 8 MVC | **5–6s → ~1s** and **30–40s → under 1s** load times |

Also built: Azure AD sign-in with MSAL that avoids a full resync for returning users, a multi-view scheduling calendar, and web reports on technician time use and budget adherence. Stack: C#, .NET MAUI, ASP.NET MVC, SQL Server, Azure DevOps CI/CD.

---

## 🚀 Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [**EvalNow Lite**](https://github.com/faizkhan005/evalnow-lite) | Backend for blind mutual evaluations: neither party sees the other's review until both submit. Row-level locking (`SELECT ... FOR UPDATE`) prevents lost updates, blindness is enforced in SQL, and refresh tokens rotate with reuse detection. | Python · FastAPI · PostgreSQL |
| [**ERP Inventory API**](https://github.com/faizkhan005/Erp-Inventory-API) | Inventory REST API with JWT auth and refresh-token rotation, Redis cache-aside caching, and cursor-based pagination. | .NET 10 · PostgreSQL · Redis · Docker |
| [**Distributed Task Queue**](https://github.com/faizkhan005/Distributed-Task-Queue) | Background job service with retries and exponential backoff, a dead-letter queue, and a full job lifecycle audit trail. | .NET 10 · Hangfire · PostgreSQL · Redis |
| [**Expense Tracker**](https://github.com/faizkhan005/ExpenseTracker) | Offline-first personal finance app with on-device receipt OCR, spending charts, and recurring expenses. | .NET MAUI · SQLite · LiveCharts2 · ML Kit |

---

## 🛠️ Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Backend & Frameworks**

![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![.NET 8/10](https://img.shields.io/badge/.NET%208%2F10-512BD4?style=flat&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF%20Core-512BD4?style=flat&logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Hangfire](https://img.shields.io/badge/Hangfire-0080FF?style=flat&logo=dotnet&logoColor=white)

**Mobile**

![.NET MAUI](https://img.shields.io/badge/.NET%20MAUI-512BD4?style=flat&logo=dotnet&logoColor=white)
![Xamarin](https://img.shields.io/badge/Xamarin-3498DB?style=flat&logo=xamarin&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

**Databases & Caching**

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**Cloud, DevOps & Auth**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D4?style=flat&logo=azure-devops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![Azure AD](https://img.shields.io/badge/Azure%20AD-0078D4?style=flat&logo=microsoft-azure&logoColor=white)
![MSAL](https://img.shields.io/badge/MSAL-0078D4?style=flat&logo=microsoft&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=json-web-tokens&logoColor=white)

**Machine Learning (coursework)**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---

## 🎓 Education

**MS, Computer Engineering · NYU Tandon School of Engineering** *(Sep 2026 to Dec 2027)*
- Fall 2026: Machine Learning, Computer Architecture, Real-Time Embedded Systems
- Spring 2027: MLOps

**BE, Computer Science · Vidyavardhaka College of Engineering (VTU)** *(2019 to 2023)*

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-peach-iota-79.vercel.app/api?username=faizkhan005&show_icons=true&theme=dark&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats-peach-iota-79.vercel.app/api/top-langs/?username=faizkhan005&layout=compact&theme=dark&hide_border=true&langs_count=8" height="150"/>
</div>

---

## 📬 Let's Connect

I'm looking for **Summer 2027 internships and part-time roles in NYC** in backend, forward deployed, and applied AI engineering. If you're working on systems that have to stay correct when things go wrong, I'd like to talk.

- 🌐 [Portfolio](https://faizkhan005.github.io/)
- 💼 [LinkedIn](https://www.linkedin.com/in/faizan-ahmed-khan-814521191)
- 📧 [Email](mailto:faizanahmedkhan005@gmail.com)
