# METICULY - Customer Registration Portal

## ✨ Features
- Register/Activate new user
- User login/logout
- Users & Roles Management  (available for only Admin roles)
- Customers Register (available for only Admin roles) otherwise READ-ONLY
  - Supported the unige customer FirstName and LastName
  - Supported auto correct word spelling (Fistname, Lastname and Email) 


## 🧰 Tech Stack
  - Python3/Flask (Buleprint) Frameworks REST API
  - JWT Authorization (Stored token in cookies, Token lifetime only 30 mins + refresh Token 30 mins)
  - JAVASCRIPT, JQuery, JgGrid (for fontend UI GRID)
  - Sqlite3
  - Spelling checking & Auto correct Email REST API (External)

## 🚀 Getting Started
-
       ```bash
          
          git clone https://github.com/Chananantachot/METICULY.git
         
         cd METICULY/src
         
         git checkout -b master
         
         python3 -m venv .venv
         
         . .venv/bin/activate
         
         pip3 install -r requirement.txt
         
         ./start.sh

  - One you seen 127.0.0.1:5000/ in your terminal/powershall
  - Visit the site at https:// 127.0.0.1:5000/
  - then open your new Terminal, then following instructions
  - 
      ```bash
       cd METICULY/src
       flask seed

 - come back to your browser you should be able to login with
     user name: admin@gmail.com
     password:  @dmin!23456
      
  
