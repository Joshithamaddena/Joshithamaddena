# Bid - Auction Platform

> The main purpose our website is, to give a virtual platform to the sellers who are interested to put their product for online selling via Bidding. And the bidders who are interested to buy and bid for the rare and best things. 

Let’s Visit our Website “Auction” – An interactive and User friendly Virtual Platform for auction!!

![signup](https://github.com/user-attachments/assets/c3e795a8-769c-4bc3-9b2a-d01cf3adb230)
![login](https://github.com/user-attachments/assets/c993b3b6-5ad2-4977-a971-23699e460743)
![welcome](https://github.com/user-attachments/assets/7e8e3bee-9210-4d3f-bfe5-52d534bf9548)
![auction](https://github.com/user-attachments/assets/1e483b7b-9d96-47b2-b2f2-ff9032060d6a)
![questions](https://github.com/user-attachments/assets/1004df54-efc6-4bf3-858b-ee33df1aac50)




## Technologies

- Frontend - React.js ,HTML, CSS
- Backend - Node js , Express
- Database - MongoDB


## SET-UPS

The application includes two modules (frontend and Backend). For local developement, run `npm install` in frontend and backend both directory which will install all dependencies accordingly. Before running this command please make sure your environment variables are setup accordingly.

### PROJECT SETUP

#### What you need to run this code
1. Node JS
2. NPM  or Yarn 
3. MongoDB 
4. Stripe account with test data
5. Cloudinary account to store images.

####  How to run this code
1. Make sure MongoDB is running on your system. 
2. Clone this repository.
3. Update config.env with your MongoDB URI and Secret Key
4. Open command line in the cloned folder,
   - To install dependencies, run ```  npm install  ```  , for frontend and backend both directory.
   - To run the application , run ```  node app.js  ``` or ```  nodemon app.js  ```  , for backend side.
   - And run ```  npm start  ``` , for frontend side.
5. Open [localhost:3000](http://localhost:3000/) in the browser

### Env Variables

Inside config.env

```
PORT = 3000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'

```


### Install Dependencies (frontend & backend)

```
# Open frontend
npm install
# Open  backend
npm install
```

### Run

```
# Run Client
npm start

# Run Server
node app.js 
#or
nodemon app.js
```



