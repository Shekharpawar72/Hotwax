# 🛒 Basic E-Commerce Website (JavaScript Project)

## 📌 Project Overview
This is a **frontend-based e-commerce website** built using **HTML, CSS, and Vanilla JavaScript**.  
The project demonstrates core JavaScript concepts such as **DOM manipulation, form handling, API integration, state management, and localStorage usage**.

The application includes **user authentication**, **product listing from a public API**, **search & filter**, and a **shopping cart system** with data persistence.

---

## 🎯 Features

### 🔐 Authentication
- User Registration (Name, Email, Password, Confirm Password)
- User Login with validation
- Email format and password length validation
- Data stored in `localStorage`
- Redirect to shop page after successful login

### 🏠 Shop Page
- Fetch products from **FakeStore API**
- Display product:
  - Image
  - Title
  - Price
  - Category
- Search products by name
- Filter products by category
- Loading spinner while fetching API data

### 🛒 Cart Functionality
- Add products to cart
- Cart is user-specific (based on logged-in user)
- Increase quantity if product already exists
- Remove items from cart
- Cart data persists using `localStorage`
- Display total cart price

### 🎨 UI
- Clean and simple UI (manual CSS, no frameworks)
- Responsive layout using Flexbox & Grid
- Assignment-friendly design (no heavy animations)

---

## 🛠️ Technologies Used
- HTML5
- CSS3
- JavaScript (ES6)
- FakeStore API
- Browser `localStorage`

---

## 📂 Project Structure

