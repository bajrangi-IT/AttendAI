

AttendAI 🏫-

(PREVIEW AVAILABLE AT           https://acad-spark.netlify.app/)

![GitHub Repo stars](https://img.shields.io/github/stars/bajrangi-IT/AttendAI?style=social)
![GitHub forks](https://img.shields.io/github/forks/bajrangi-IT/AttendAI?style=social)
![GitHub issues](https://img.shields.io/github/issues/bajrangi-IT/AttendAI)
![License](https://img.shields.io/github/license/bajrangi-IT/AttendAI)

**AttendAI** is an all-in-one **attendance management system** for educational institutions. It provides **real-time attendance tracking**, **role-based dashboards**, **timetable management**, and **announcement handling** for students, teachers, and HODs, built with modern, scalable web technologies.

---

## 📌 Built With

- **Frontend:** React, Vite, TypeScript, Tailwind CSS, shadcn-ui  
- **Backend & Database:** Supabase (Database + Serverless Functions)  
- **Authentication:** Secure role-based login  
- **Tools & Version Control:** Git, GitHub  

---

## 📌 Features

### Student
- View attendance  
- Receive announcements  
- Access timetable  

### Teacher
- Mark attendance  
- Submit extra lecture requests  
- Track request status  

### Head of Department (HOD)
- Manage students & teachers  
- Approve/reject lecture requests  
- Generate & manage timetables  
- Make announcements  
- Monitor overall attendance  

### Key Functionalities
- Role-based dashboards  
- Real-time updates with Supabase  
- Serverless functions for backend logic  
- Modern, responsive UI  

---

## 📌 How It Works

```mermaid
flowchart TD
    A[Login / Authentication] --> B{User Role}
    B -->|Student| C[Student Dashboard]
    B -->|Teacher| D[Teacher Dashboard]
    B -->|HOD| E[HOD Dashboard]
    C --> F[View Attendance & Announcements]
    D --> G[Mark Attendance & Request Extra Lectures]
    E --> H[Manage Users, Approve Requests, Generate Timetable]
````

---

## 📌 Screenshots

**Student Dashboard**
![Student Dashboard](screenshots/student_dashboard.png)

**Teacher Dashboard**
![Teacher Dashboard](screenshots/teacher_dashboard.png)

**HOD Dashboard**
![HOD Dashboard](screenshots/hod_dashboard.png)


---

## 📌 Installation

1. **Fork** this repository.
2. **Clone** it locally:

   ```bash
   git clone https://github.com/bajrangi-IT/AttendAI.git
   ```
3. Navigate into the project directory:

   ```bash
   cd AttendAI
   ```
4. Install dependencies:

   ```bash
   npm install
   ```
5. Create a `.env` file with your **Supabase credentials**.
6. Run the development server:

   ```bash
   npm run dev
   ```
7. Open the provided localhost URL in your browser.

---

## 📌 Contributing

Contributions are welcome! Please **fork the repo** and create a **pull request**. For major changes, open an **issue** first to discuss.

---

## 📌 Author

👤 **Ashutosh Sharma**

* [GitHub](https://github.com/bajrangi-IT)
* [LinkedIn](https://www.linkedin.com/in/ashutosh-sharma-3a685b382/)
* [Instagram](https://www.instagram.com/ashu.devops/)
---

## 📌 Show Your Support

If you like this project, please ⭐️ the repository to show your support!

---

## 📌 License

This project is **MIT licensed**.


```
