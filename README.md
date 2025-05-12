# 📚 Course Management System

A Windows Forms (WinForms) application built with C# for managing courses, students, and teachers, with integrated financial tracking and data visualization. This desktop app is powered by Microsoft SQL Server for backend data management and supports dynamic reporting and XML export.

---

## 🧩 Features

### 👥 Data Management
- Add, edit, and remove **courses**, **teachers**, and **students**.
- Track **student payments** and **billing information**.
- Manage **student enrollment** per course.

### 📘 Course Lifecycle
- Courses require **minimum 4** and a maximum of **8 students** to start.
- Courses are **inactive by default** and must be manually activated.
- On activation, set **start date** and **cost per student**.
- Courses can be **closed** by setting an **end date**.

### 📊 Queries & Reports
- Search for teachers and list their associated courses (active & closed).
- Modify active course details as needed.
- Generate:
  - **Pie charts** showing student distribution per teacher over time.
  - **Line charts** for revenue trends across courses.
- Export course details and student lists to **XML**.

---

## 🛠️ Tech Stack

| Technology | Description |
|-----------|-------------|
| **C# WinForms** | User interface and desktop functionality |
| **Microsoft SQL Server** | Data persistence and relational storage |
| **System.Windows.Forms.DataVisualization** | Built-in charting for visual analytics |
| **XML Serialization** | Exporting structured data for backup or sharing |

---

## 🚀 Getting Started

### ✅ Prerequisites
- Microsoft SQL Server (running locally or remotely)
- .NET Framework (compatible with WinForms)

### 📦 Installation

```bash
git clone https://github.com/yourusername/course-management-system.git
```

## 🧪 Usage

- Create and manage **teachers**, **students**, and **courses**.
- Register students into courses and activate courses when criteria are met.
- Track and manage **payments**.
- View **analytics** via charts.
- Export course and student data to **XML** for offline use or reporting.

## 🧑‍💻 Author

**DraymeM** – Desktop Application Developer, Database Architect

## 🙌 Acknowledgments

- Microsoft Docs and SQL Server community for guidance on best practices  
- .NET WinForms and Data Visualization libraries  
- XML serialization resources for structured data handling

