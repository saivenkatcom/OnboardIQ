# 🎯 OnboardIQ — Developer Onboarding Accelerator

> A smart platform that reduces developer onboarding time from 90 days to under 30 days using intelligent codebase mapping, role-based learning paths, and AI-assisted Q&A.

---

## 🏗️ Tech Stack

| Layer | Technology |
|---|---|
| **Backend** | .NET 8 Web API (Clean Architecture) |
| **Frontend** | Angular 17+ with SCSS |
| **Database** | SQL Server + Entity Framework Core |
| **Auth** | JWT Bearer Authentication |
| **Real-time** | SignalR |
| **API Docs** | Swagger / OpenAPI |

---

## 📁 Project Structure

```
OnboardIQ/
├── OnboardIQ.sln
├── OnboardIQ.API/              ← ASP.NET Core Web API
│   ├── Controllers/
│   ├── Program.cs
│   └── appsettings.json
├── OnboardIQ.Core/             ← Domain (Entities, Interfaces, DTOs)
│   ├── Entities/
│   ├── Interfaces/
│   └── DTOs/
├── OnboardIQ.Infrastructure/   ← Data access, Services, Repos
│   ├── Data/
│   ├── Repositories/
│   └── Services/
├── onboardiq-client/           ← Angular Frontend
│   ├── src/app/
│   └── ...
└── operations_log.txt          ← Operation history log
```

---

## 🚀 Features

- 🗺️ **Codebase Map** — Visual architecture explorer
- 📋 **Learning Paths** — Role-based onboarding sequences
- 🤖 **Smart Q&A** — AI-assisted developer assistant
- 📊 **Progress Tracker** — Milestone dashboard
- 🔗 **Ticket-to-Code Linking** — Maps Jira tasks to code modules
- 📅 **Mentor Alerts** — Notifies when new hires are stuck
- 🏆 **Readiness Score** — Quantifies onboarding progress

---

## ⚙️ Getting Started

### Backend
```bash
cd OnboardIQ.API
dotnet restore
dotnet run
```

### Frontend
```bash
cd onboardiq-client
npm install
ng serve
```

---

## 📄 License
MIT
