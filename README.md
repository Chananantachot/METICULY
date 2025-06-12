# METICULY - Customer Registration Portal

## ✨ Features
- Register/Activate new user
- User login/logout
- Users & Roles Management  (available for only Admin roles)
- Customers Register (Create/Update only available for Admin role users).
  - Supported the uniqe customer FirstName and LastName
  - Supported auto correct word spelling (Fistname, Lastname and Email) 


## 🧰 Tech Stack
  - Python3/Flask (Buleprint) Frameworks REST API
  - JWT Authorization (stored Token in cookies, Token & Cookies lifetimes will be 30 mins + Refresh Token 30 mins) after an hour user will need to re-login.
  - CSS,JAVASCRIPT, JQuery, JqGrid (for fontend UI GRID)
  - Sqlite3 (local database)
  - Intergated spelling checking & auto correct email via external REST API 

## 🚀 Getting Started
    ```bash
         git clone https://github.com/Chananantachot/METICULY.git 
         cd METICULY/src
         python3 -m venv .venv
         . .venv/bin/activate
         pip3 install -r requirement.txt
         ./start.sh

  - Visit the site at https:// 127.0.0.1:5000/
  - then open your new Terminal, then following instructions
      User Name: admin@gmail.com
      Password:  @dmin!23456
        
  
