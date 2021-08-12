# Accounting

App that can take transactions and put them in an accounting tabel
    Accounting(transaction) table columns: 
    "Id"(automatic generation),
    "name (user input)", 
    "transaction Type"(custom types with default "importance"), 
    "Description", 
    "Amount", 
    "total", (effect of all the transaction chosen) - maybe at the end and not as a column
    "timeStamp",
    "Transaction importance"{
        standard income, bonuses, temporary holding  
        necessary, special, makes better, pleassure, unnecesary
    },
    "transaction effect" (debit/credit), 

    User previlage
        Admin
            can create new transaction types
            can add transactions
        User
            can add transactions 

App Development (Story Name)

    - Create App (acc-1)
        . Create an app in react 
        . Add Redux store to the app

    - Create Login Page
        . User can enter username(which is email) and password
        . Static Credential Authentication with values from a json file
        . Authontication should set user previlages (admin) if exists
        . App should hold user's name for display 