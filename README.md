
## 📌 FindHelper

**FindHelper** is a web-based application designed to connect users with skilled professionals (like plumbers, electricians, cleaners, etc.) based on location, availability, and service category. The platform allows both customers and service professionals to register, interact, and manage bookings in a user-friendly interface.

### 🚀 Live Demo

🌐 **Live URL**: [https://findhelper.onrender.com](https://findhelper.onrender.com)

---

### 📁 Project Structure

* **Frontend**: React-based user interface.
* **Backend**: JSON Server (Mock API).
* **Database**: `db.json` (serves as the database for users, professionals, bookings, etc.)

---
## ✨ Features

- 👤 User Login and Registration  
- 🛠️ Professional Login and Registration  
- 🧑‍💼 Admin Login with Dashboard  
- 🔍 Browse available professionals by category  
- 📅 Book appointments with professionals  
- ✅ Professionals can accept or reject bookings  
- 📊 Admin can view and manage all users, professionals, and bookings  
- 🔁 Real-time status updates of bookings  
- 🏠 Clean and user-friendly interface  
- 💡 Alerts and validations for smoother experience  
- 🧪 Mock backend using `json-server`

---


### 🛠️ Tech Stack

* **Frontend**: HTML,CSS,JS
* **Backend**: JSON Server
* **Deployment**: Render

---

### ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/DurgaBhavani25/FindHelper.git
   cd FindHelper
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Run JSON Server**

   ```bash
   npx json-server --watch db.json --port 10000
   ```

4. **Start React App**

   ```bash
   npm start
   ```

5. Open `http://localhost:3000` in your browser.

---

### 🔗 API Endpoints

* `GET /users`
* `GET /professionals`
* `GET /customers`
* `GET /admins`
* `GET /bookings`

> All served from: `http://localhost:10000/`

---

### 📸 Screenshots

<img width="1885" height="806" alt="image" src="https://github.com/user-attachments/assets/d9a15a42-d631-4b19-8f1f-56c618be1cba" />

---

### 🧑‍💻 Author

**Poosarla Durga Bhavani**
[GitHub](https://github.com/DurgaBhavani25)

---

### 📃 License

This project is licensed under the MIT License.

---

