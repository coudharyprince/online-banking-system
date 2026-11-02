# Online Banking System

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Angular-1a1b27?style=for-the-badge&logo=angular&logoColor=DD0031"/>
  <img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/.NET%20C%23-1a1b27?style=for-the-badge&logo=dotnet&logoColor=512BD4"/>
  <img alt=".NET C#" src="https://img.shields.io/badge/.NET%20C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/SQL-1a1b27?style=for-the-badge&logo=mysql&logoColor=4479A1"/>
  <img alt="SQL" src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/HTML5-1a1b27?style=for-the-badge&logo=html5&logoColor=E34F26"/>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/CSS3-1a1b27?style=for-the-badge&logo=css&logoColor=1572B6"/>
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white"/>
</picture>

A comprehensive full-stack online banking application. Built with **Angular** on the frontend and **.NET C# backend services** over **SQL**, it serves thousands of users with account management, fund transfers, transaction history, and statement generation — secured with role-based access control across customer and admin interfaces.

---

## ✨ Features

- **Account Management** — create and manage bank accounts with a complete overview of balances and account details
- **Fund Transfers** — move money between accounts with validation and confirmation flows
- **Transaction History & Statements** — browse past transactions and generate account statements
- **Role-Based Access Control (RBAC)** — secure authentication and authorization across **customer** and **admin** interfaces
- **Responsive UI** — Angular Material components delivering a seamless experience across desktop and mobile devices
- **Banking-Grade Security** — authentication and authorization mechanisms implemented in line with banking security standards and data protection regulations
- **Performance** — database query and application performance optimization delivering **25% faster page loads**

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Angular, Angular Material, HTML5, CSS3 |
| Backend | .NET C# backend services |
| Database | SQL (with query optimization) |
| Tooling | Visual Studio, VS Code, Git, GitHub, SQL Server Management Studio |

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm (with the Angular CLI: `npm install -g @angular/cli`)
- [.NET SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server) (SSMS recommended for running the database scripts)

### Setup

```bash
# 1. Clone the repository
git clone https://github.com/coudharyprince/online-banking-system.git
cd online-banking-system

# 2. Database — execute the SQL scripts in database/ on your SQL Server
#    instance, then update the connection string in the API's appsettings.json

# 3. Run the .NET backend
cd server
dotnet restore
dotnet run

# 4. Run the Angular frontend (in a new terminal)
cd client
npm install
npm start
```

Open `http://localhost:4200` in your browser. Log in as a **customer** or an **admin** — the interfaces and permissions differ by role.

---

## 📁 Project Structure

```
online-banking-system/
├── client/                 # Angular frontend
│   └── src/app/
│       ├── core/           # authentication, interceptors, shared services
│       ├── shared/         # reusable Angular Material components
│       ├── customer/       # customer-facing modules (accounts, transfers, statements)
│       └── admin/          # admin-facing modules (RBAC-protected)
├── server/                 # .NET C# backend services
│   ├── Controllers/        # API endpoints
│   ├── Models/             # entities and DTOs
│   └── Services/           # business logic
└── database/               # SQL schema and scripts
```

---

## 🔐 Security Notes

- **Role-based access control** keeps the customer and admin experiences strictly separated — every interface is protected by the user's role
- **Secure authentication and authorization** mechanisms are applied end to end, following banking security standards and data protection regulations
- Sensitive operations (transfers, statement generation) are validated server-side by the .NET backend services

---

## ⚡ Performance

Database queries and application performance were profiled and optimized at scale — the platform serves thousands of users with **25% faster page loads** and a measurably smoother user experience.

---

## 👤 Author

**Prince Kumar**

<a href="mailto:prince.kr991@outlook.com"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Email-1a1b27?style=for-the-badge"/>
  <img alt="Email" src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge"/>
</picture></a>
<a href="tel:+917808501582"><picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://img.shields.io/badge/Phone-1a1b27?style=for-the-badge"/>
  <img alt="Phone" src="https://img.shields.io/badge/Phone-25D366?style=for-the-badge"/>
</picture></a>

---

*If this project helped you, please consider giving it a ⭐!*
