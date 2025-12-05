
# Employee Management System – C++ Console Application

This project is a basic **Employee Management System** developed in C++.  
It includes user registration, employee login, salary/leave/insurance calculations, and a boss (admin) panel.

---

## 📝 Features

### ✔ User Registration
- Employees can register by selecting their employment status (full-time, part-time, intern).
- Each user receives a unique **personal number**.
- All user data is stored in a `.txt` file.

### ✔ Employee Login
Employees can log in using:
- Personal number  
- Username  
- Password  

After logging in, they can:
- Calculate monthly **salary**
- View monthly **leave entitlement**
- Calculate **insurance cost**

All calculations depend on the employee’s status.

### ✔ Boss Login (Admin Panel)
- Accessible only with the special personal number **0001**.
- The boss can:
  - View all registered employees
  - See usernames and employee status
  - Display boss-specific salary, leave, and insurance details

### ✔ Object-Oriented Structure
The project uses several classes:
- `EmployeeInfo` – Handles salary, leave, and insurance calculations  
- `UserMemory` – Manages user registration and login  
- `Boss` – Admin-only operations  
- `MainMenu` – Main menu and navigation  

---

## 🛠 Technologies Used
- C++  
- File Handling (`fstream`)  
- Object-Oriented Programming (OOP)

---

## 🚀 How to Run
1. Compile the program using a C++ compiler (g++, MSVC, etc.).
2. Run the generated executable.
3. Use the menu to sign up or log in as an employee/boss.

---

## 📌 Notes
- Personal numbers must be remembered; they are required for login.
- Boss mode is only accessible through the code-defined ID `0001`.

---

## 📂 File Output
User data is saved in:


