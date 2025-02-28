---

# 🚌 Bus Booking System API  

## 📌 Overview  
This repository contains the **backend API** for a **Bus Booking System**, built using **Express.js** and **MongoDB**. The API supports **authentication, authorization, bus and route management, and user bookings**.  

---

## 🔑 Admin Credentials  
Use the following credentials to authenticate as an **admin**:  

```json
{
  "username": "AnthillNetworks",
  "email": "anthillnetworks@example.com",
  "password": "password123"
},
{
  "username": "Rithiga",
  "email": "Rithiga@example.com",
  "password": "password123"
}
```

---

## 🛠 Features  

### ✅ **Admin Functionalities**  
✔ Manage users (View, Update, Delete)  
✔ Add and update bus details  
✔ Add and update routes  
✔ View all bookings  

### 🏷 **User Functionalities**  
✔ Search for buses  
✔ Book and cancel bus tickets  
✔ Add and delete reviews  

### 📑 **Additional Features**  
✔ **JWT-based authentication** for security  
✔ **API documentation** via Swagger  
✔ **Postman Collection** available for easy testing  

---

## 🧪 API Testing  

### 📜 **Swagger API Documentation**  
- View and test API endpoints using Swagger:  
  🔗 [Swagger Docs](https://anthill-backend-1.onrender.com/api-docs)  

### 📩 **Postman Collection**  
- To test APIs using **Postman**, import the collection file:  
  `Anthill-Networks-Bus.postman_collection.json`  

---

## ⚙️ Installation & Setup  

### 1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/rithigavijayendran/Anthill-Backend.git  
cd Anthill-Backend  
```

### 2️⃣ **Install Dependencies**  
```sh
npm install  
```

### 3️⃣ **Setup Environment Variables**  
Create a `.env` file and configure:  
```sh
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

### 4️⃣ **Start the Server**  
```sh
node index.js  
```
The server will start running on **http://localhost:5000**  

---
