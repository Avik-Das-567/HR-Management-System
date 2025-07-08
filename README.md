# Flask App - HR Management System
---
## What is an HR Management System?
- An **HR Management System** is used to **store**, **view**, **update**, and **delete** employee records.
- It includes full **CRUD** operations :

   - **Create** – Add new employee
  - **Read** – View all employees
  - **Update** – Edit employee info
  - **Delete** – Remove employee record
---
## Folder Structure
```
HR-Management-System/
│
├── app.py  
└── templates/
    ├── home.html  
    └── edit.html
```
---
## How to Run Locally
- Go to the **HR-Management-System** folder in your PC, and open **Command Prompt** in that folder.

- In the CMD, type :
  ```
  python -m venv venv  
  ```
  This creates a **virtual environment** named `venv`.

- Activate the **Virtual Environment** :
  ```
  venv\Scripts\activate
  ```
- Install **flask** and **flask-sqlalchemy** (if not installed already).
  ```
  pip install flask flask-sqlalchemy
  ```
- Run the app :
  ```
  python app.py
  ```
- Go to this link in browser :
  ```
  http://127.0.0.1:5000
  ```
---
## Preview Image of the Web Page : 
![HR-Management-Screenshot](https://github.com/user-attachments/assets/3a02792a-831c-4454-87cf-d4cc1d175e87)

---
