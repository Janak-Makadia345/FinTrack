# 💰 FinTrack: Financial Management System 📊

A secure, role-based financial web application for small-to-medium businesses to manage daily cash flow, transactions, and generate insightful financial reports.

🔗 [GitHub Repository](https://github.com/Janak-Makadia345/FinTrack.git)

---

## 📌 About

**FinTrack** is a full-featured web application built to support **multi-user, multi-business** financial record-keeping. The system supports secure login, role-based access, dynamic filtering, visual dashboards, and reporting features across **5+ core financial modules**.

---

## ✨ Features

- 🔐 Secure **authentication**, **cookie-based sessions**, and **HTTPS**
- 🏢 Multi-business support — managing **500+ users** across **5+ companies**
- 🔍 Advanced **search, filter, sort** for **10,000+ records**
- 📊 Real-time **dashboards** for:
  - 💸 Cash Flow
  - 📒 Daybook
  - 📈 Profit & Loss
- 📤 Export to CSV/PDF
- ✅ Full **CRUD operations**
- 🧑‍💼 **RBAC**: Role-Based Access Control
- 🧾 Modules: Users, Transactions, Daybook, Accounts, Reports, Settings

---

## 🧠 Highlights (from Resume)

- 🔐 **Built** a secure app with HTTPS, cookie sessions, and RBAC handling **500+ users** for **5+ businesses**
- ⚙️ **Integrated** dynamic filters, sort, and search across **10,000+ financial records** cutting query time by **45%**
- 📈 **Designed** visual dashboards with financial reports for **1000+ monthly transactions**
- 💾 **Implemented** CRUD, export, and modular RBAC using **SQL Server** + **Entity Framework**

---

## 🛠 Tech Stack

### 🔧 Backend
- 🟦 **C# / .NET Core**
- 🧠 **Entity Framework Core (EF)**
- 🗄️ **SQL Server** — structured financial data

### 🌐 Frontend
- ⚛️ **React.js** or Razor Views (depending on implementation)
- 🎨 **Bootstrap / Tailwind CSS** for UI
- 🔁 **AJAX** or Axios for async interactions

### 🔐 Security
- ✅ **HTTPS**
- 🍪 **Session-based auth** using encrypted cookies
- 🧑‍⚖️ **Role-Based Access (RBAC)**

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Janak-Makadia345/FinTrack.git
cd FinTrack
```

### 2️⃣ Configuration

Create `appsettings.json` with your connection string:
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=.;Database=FinTrackDB;Trusted_Connection=True;"
  },
  "AppSettings": {
    "JwtSecret": "YourSuperSecretKey"
  }
}
```

### 3️⃣ Database Setup (EF Core)

```bash
# In Package Manager Console
Update-Database
```

Or use CLI:
```bash
dotnet ef database update
```

### 4️⃣ Run the Application

```bash
dotnet run
```

Visit: [https://localhost:5001](https://localhost:5001)

---

## 📦 Modules Overview

| Module       | Features                                      |
|--------------|-----------------------------------------------|
| Users        | Registration, login, role management          |
| Transactions | Add/Edit/Delete transactions with filters     |
| Daybook      | Real-time transaction logs                    |
| P&L Report   | View profit & loss monthly summaries          |
| Cash Flow    | Track incoming/outgoing cash                  |
| Export       | Download CSV/PDF of reports                   |

---

## 📈 Dashboards & Reports

- 📆 Filter by Date Range
- 🧾 Cash In vs Cash Out graph
- 📉 Net Profit tracking
- 📊 Monthly breakdowns (bar/line/pie charts)

---

## 🧪 Testing (Optional)

```bash
dotnet test
```

---

## 🐛 Contributing

1. 🍴 Fork the repository  
2. 🌱 Create your feature branch: `git checkout -b feature/AmazingFeature`  
3. 💾 Commit your changes: `git commit -m 'Add some AmazingFeature'`  
4. 📤 Push to the branch: `git push origin feature/AmazingFeature`  
5. 📬 Open a Pull Request  

---

## 👨‍💻 Author

Made with 💡 by [Janak Makadia](https://github.com/Janak-Makadia345)

Feel free to ⭐️ the repo and connect if this project helped you!

---

## 📬 Contact

For collaboration, feedback, or tech talk:

📧 makadiask901@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/janak-makadia)

