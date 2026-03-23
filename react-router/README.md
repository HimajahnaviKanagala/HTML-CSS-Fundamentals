# React Router & Protected Routes ⚛️

This project demonstrates routing, navigation, and basic authentication in React using React Router. It includes multiple pages, dynamic routing, and protected routes that restrict access based on login status.

---

## 🚀 Technologies Used

* React
* React Router DOM
* JavaScript (ES6+)
* CSS
* Vite

---

## 📚 Concepts Covered

### 1. React Router Basics

* BrowserRouter for routing setup
* Routes and Route for defining paths
* Navigation using Link and NavLink

---

### 2. Navigation

* Navigation between pages without reload
* Active link styling using NavLink
* Programmatic navigation using useNavigate

---

### 3. Dynamic Routing

* URL parameters using `:id`
* Accessing params using `useParams`
* Fetching data based on route parameter

---

### 4. Protected Routes (Authentication)

* Restricting access to certain pages
* Redirecting unauthorized users to login page
* Using a custom ProtectedRoute component

---

### 5. Conditional Rendering

* Showing Login/Logout buttons based on authentication state
* Hiding protected links when user is not logged in

---

## 🔐 Authentication Flow

* User logs in using email and password
* Login status stored in localStorage
* Protected routes check login status
* Unauthorized users are redirected to login page
* Logout removes login state

---

## 🧩 Components & Pages

* Home → Landing page
* About → Information page
* Products → List of products (Protected)
* ProductDetail → Dynamic product page (Protected)
* Contact → Form page
* Login → Authentication page
* NotFound → 404 error page
* Navbar → Navigation with Login/Logout buttons

---

## 🧩 Key Features

* Multi-page navigation using React Router
* Dynamic routes (`/products/:id`)
* Protected routes using custom wrapper
* Login & Logout functionality
* Conditional rendering in Navbar
* 404 Not Found page
* API data fetching (DummyJSON)

---

## 📁 Project Structure

```id="p9x4tm"
src
 ├── components
 │     ├── ProtectedRoute.jsx
 │
 ├── pages
 │     ├── Home.jsx
 │     ├── About.jsx
 │     ├── Products.jsx
 │     ├── ProductDetail.jsx
 │     ├── Contact.jsx
 │     ├── Login.jsx
 │     ├── NotFound.jsx
 │     ├── Navbar.jsx
 │
 ├── App.jsx
 ├── main.jsx
 └── styles.css
```

---

## ▶️ Getting Started

Install dependencies:

```bash id="x1b2c3"
npm install
```

Run the development server:

```bash id="y4z5k6"
npm run dev
```

Open in browser:

```id="m7n8p9"
http://localhost:5173
```

---

## 🔑 Login Credentials (Demo)

```id="cred01"
Email: admin@gmail.com
Password: admin@123
```

---

## 🎯 Learning Outcomes

By building this project, I learned:

* How to implement routing using React Router
* How to create dynamic routes with parameters
* How to protect routes based on authentication
* How to handle navigation programmatically
* How to manage UI based on login state
* How to build a multi-page React application

---

