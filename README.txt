Alambile - Our Food/Waste Management App

1.Run -  git clone https://github.com/kavyadayanand/cmpe_272.git 
    a.After cloning cd to almabile folder

How to run backend code: 
1. cd backend
2. npm i
3. npm app.js
server will start at 3001 port localhost:3001

How to run frontend code:
1. cd frontend
2. npm i
3. npm start
server will start at 3000 port localhost:3000


Database:


Start mongodb using command 

mongod  in your terminal

Database name: Users
Collection tables:
1. login(with below json fields)
{
    "username" : "kavyad@gmail.com",
    "password" : "alambile"
}
2. restaurant(sign up page details)
{
    "firstname" : "Sid",
    "restaurantName" : "Rangoli",
    "email" : "sid1@gamil.com",
    "address" : "265 Union Avenue Campbell",
    "city" : "San Jose",
    "zipcode" : 95008,
    "password" : "1234"
}

3. volunteer (sign up page details)
{
    "firstname" : "Nand",
    "email" : "nand@gmail.com",
    "address" : "Apt 80, Campbell",
    "city" : "San Jose",
    "zipcode" : 95126,
    "password" : "1234"
}
