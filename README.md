# 🛍️ ShopSphere

ShopSphere is a full-stack e-commerce web application where users can browse products, view product details, and manage products through a connected frontend and backend API.

The project is built using **React.js** for the frontend and **Node.js with Express.js** for the backend.

---

## ✨ Features

* 🏠 Modern home page
* 📦 Display products from the backend API
* ➕ Add new products
* ✏️ Update product information
* 🗑️ Delete products
* 🔍 Product information and details
* 🔗 React frontend connected with REST API
* 📡 Backend API for product management
* 💾 Database integration
* 📱 Responsive user interface

---

## 🛠️ Technologies Used

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3
* Vite
* Fetch API

### Backend

* Node.js
* Express.js
* REST API

### Database

* MongoDB / Database used by the backend

### Development Tools

* Visual Studio Code
* Git
* GitHub
* npm

---

## 📋 Requirements

Before running this project, install the following:

### 1. Node.js

Install **Node.js** on your computer.

Check the installation:

```bash
node --version
npm --version
```

### 2. Git

Git is required if you want to clone or manage the project using Git.

Check:

```bash
git --version
```

### 3. Database

Make sure your database is installed/configured and running if your backend requires a local database.

### 4. Code Editor

You can use:

* Visual Studio Code
* IntelliJ IDEA
* Any other JavaScript-compatible editor

---

# 🚀 Installation and Setup

## 1. Clone the Repository

```bash
git clone https://github.com/supriyatiwari148/ShopSphere.git
```

Move into the project folder:

```bash
cd ShopSphere
```

---

# 📁 Project Structure

The project contains separate frontend and backend parts.

```text
ShopSphere/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   ├── server.js
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

> The exact folder names may vary depending on the current project structure.

---

# 📦 Install Dependencies

## Frontend

Open a terminal inside the frontend folder:

```bash
cd frontend
npm install
```

Start the frontend:

```bash
npm run dev
```

The frontend will normally run on:

```text
http://localhost:5173
```

---

## Backend

Open another terminal and move into the backend folder:

```bash
cd backend
npm install
```

Start the backend:

```bash
npm start
```

or, if the project uses nodemon:

```bash
npm run dev
```

The backend API runs on the configured backend port, for example:

```text
http://localhost:5000
```

---

# 🔗 API

The frontend communicates with the backend through REST API endpoints.

Example:

```text
GET /api/products
```

This endpoint is used to retrieve products.

Other product operations may include:

```text
POST   /api/products
GET    /api/products
PUT    /api/products/:id
DELETE /api/products/:id
```

---

# ⚙️ Environment Variables

If the backend uses environment variables, create a `.env` file inside the backend folder.

Example:

```env
PORT=5000
DATABASE_URL=your_database_connection_string
```

Do **not** upload your `.env` file to GitHub.

The `.gitignore` file already excludes:

```text
.env
```

---

# ▶️ Running the Complete Project

You need to run both the frontend and backend.

### Terminal 1 — Backend

```bash
cd backend
npm install
npm start
```

### Terminal 2 — Frontend

```bash
cd frontend
npm install
npm run dev
```

Then open the frontend URL shown by Vite in your browser.

---

# 🧪 Testing the Application

After starting both servers:

1. Open the ShopSphere website.
2. Check whether products are displayed.
3. Try adding a product.
4. Check whether the product appears in the product list.
5. Test updating product information.
6. Test deleting a product.
7. Check the browser console if an API error occurs.

---

# 🔒 GitHub and Security

The project uses a `.gitignore` file to prevent unnecessary or sensitive files from being uploaded.

Important ignored files/folders include:

```text
node_modules/
dist/
.env
```

Never upload:

* Database passwords
* API keys
* Secret tokens
* `.env` files
* `node_modules`

---

# 🎯 Learning Objectives

This project was developed to understand and practice:

* React component development
* React state management
* API integration
* REST APIs
* CRUD operations
* Node.js
* Express.js
* Database connectivity
* Frontend-backend communication
* Git and GitHub
* Full-stack application development

---

# 🔮 Future Improvements

Possible future improvements include:

* 👤 User authentication
* 🛒 Shopping cart
* ❤️ Wishlist
* 🔎 Advanced product search
* 🏷️ Product categories and filters
* 💳 Online payment integration
* 📦 Order management
* 👨‍💼 Admin dashboard
* ⭐ Product reviews and ratings
* 📱 Improved mobile responsiveness

---

# 👩‍💻 Author

**Supriya Tiwari**

Computer Engineering Student

GitHub:
https://github.com/supriyatiwari148

---

# 📄 License

This project is created for **educational and learning purposes**.
