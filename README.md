# Student Enrollment Form using JsonPowerDB

## 📌 Project Description
This project is a **Student Enrollment Form** developed using **HTML, Bootstrap, JavaScript, jQuery, and JsonPowerDB**.  
The form allows users to **Save, Update, and Reset** student records based on a **Primary Key (Roll Number)**.

The project is hosted using **GitHub Pages** and data is stored in **JsonPowerDB**.

---

## 🛠️ Technologies Used
- HTML5
- CSS3 (Bootstrap 3)
- JavaScript
- jQuery
- JsonPowerDB
- Git & GitHub
- GitHub Pages

---

## 🗂️ Database Details
- **Database Name:** SCHOOL-DB  
- **Table Name:** STUDENT-TABLE  
- **Primary Key:** Roll Number  

### Fields:
- Roll Number
- Full Name
- Class
- Birth Date
- Address
- Enrollment Date

---

## ⚙️ Project Features
- Primary key based validation
- Save new student records
- Update existing student records
- Reset form functionality
- Field enable/disable logic as per requirements
- Data validation (no empty fields)
- JsonPowerDB integration
- Live deployment using GitHub Pages

---

## 🔄 Working Logic
1. On page load, only **Roll Number** field is enabled.
2. User enters Roll Number:
   - If record does **not exist**, form enables **Save** option.
   - If record **exists**, data is fetched and **Update** option is enabled.
3. User can save or update data accordingly.
4. Reset button clears the form and restores initial state.

---

## 🌐 Live Project Link
👉 https://aakashsaini001.github.io/student-enrollment-jsonpowerdb/

---



## 🚀 How to Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/aakashsaini001/student-enrollment-jsonpowerdb.git
