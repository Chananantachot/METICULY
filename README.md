# METICULY - Customer Registration Portal

## ✨ Features
- Register/Activate new user
- User login/logout
- Users & Roles Management  (Only available for Admin roles)
- Customers Register (Create/Update only available for Admin role users).
  - Supported the uniqe customer FirstName and LastName
  - Supported auto correct word spelling (Fistname, Lastname and Email) 


## 🧰 Tech Stack
  - Python3/Flask (Buleprint) Frameworks REST API
  - JWT Authorization (stored Token in cookies, Token & Cookies life-times will be in 30 mins + Refresh Token in 30 mins) after an hour user will need to re-login.
  - CSS,JAVASCRIPT, JQuery, JqGrid (for fontend UI GRID)
  - Sqlite3 (local database)
  - Intergated spelling checking & auto correct email via external REST API 

## 🚀 Getting Started
         git clone https://github.com/Chananantachot/METICULY.git 
         cd METICULY/src
         python3 -m venv .venv
         . .venv/bin/activate
         pip3 install -r requirement.txt
         ./start.sh

  ### Visit the site at https:// 127.0.0.1:5000/
       Login with
          Username: admin@gmail.com
          Password:  @dmin!23456
        
  
