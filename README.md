# 🍔 Smart Campus Canteen Pre-Booking System (CanteenGo)




  <a href="https://rakeshreddy5449-blip.github.io/Smart-Campus-Food-Ordering-System/">🌐 Live Application</a> •
  <a href="https://github.com/rakeshreddy5449-blip/Smart-Campus-Food-Ordering-System">💻 GitHub Repository</a>



## 📌 1. Project Overview

The **Smart Campus Canteen Pre-Booking System (CanteenGo)** is a web-based food ordering and pre-booking application designed to improve the food ordering experience for students at SR University.

In traditional college canteens, students often spend a significant amount of time standing in queues to order and collect their food. This becomes inconvenient, especially during short breaks between classes.

To solve this problem, CanteenGo provides an online platform where students can browse the available food menu, select their favourite dishes, add items to a shopping basket, schedule their preferred collection time, and place food orders before reaching the canteen.

The main objective of this project is to reduce waiting times, simplify food ordering, improve convenience, and provide a smooth digital canteen experience.

## 🎯 2. Project Objectives

- Develop a digital food ordering platform for university students.
- Reduce long queues and waiting times in the campus canteen.
- Allow students to browse food items and their prices online.
- Provide a convenient shopping basket and checkout experience.
- Enable students to schedule their preferred food collection time.
- Generate unique order IDs and digital collection tokens.
- Provide simulated online payment and Pay at Canteen options.
- Maintain student order histories and order details.
- Create a responsive and user-friendly interface.

## ✨ 3. Key Features

### 🏠 Home Page
- Modern and attractive landing page.
- SR University campus-focused design.
- Introduction to the CanteenGo platform.
- Popular food items and food categories.
- Quick navigation to the menu, registration, and login.
- Information about the canteen ordering process.

### 👨‍🎓 Student Registration and Login
- New student registration.
- Student details collection.
- Student ID and email-based login.
- Input validation for registration forms.
- Duplicate Student ID and email checks.
- Password visibility option.
- Browser-based student demo accounts.

### 🍕 Food Menu Management
- Browse available food items.
- Display food images and descriptions.
- Show food prices in Indian Rupees (₹).
- Display food availability and ratings.
- Vegetarian and non-vegetarian labels.
- Search for food items by name.
- Filter food items by category and dietary preference.
- Sort menu items.

### 🛒 Shopping Basket
- Add food items to the basket.
- Increase or decrease item quantities.
- Remove unwanted food items.
- Automatically calculate the total price.
- Display the basket item count.
- Save basket information in browser storage.

### ⏰ Food Pre-Booking and Collection Scheduling
- Select a preferred collection date.
- Choose a convenient collection time.
- Review selected food items before ordering.
- Add optional instructions.
- Display the complete order summary.

### 💳 Payment Options

The application provides two payment methods:

**1. Pay at Canteen**
- Place an order without making an online payment.
- Payment remains pending until collection.
- Generate a unique order ID.
- Generate a digital collection token.

**2. Online Payment (Simulation)**
- UPI payment demonstration.
- Debit card payment demonstration.
- Credit card payment demonstration.
- Simulated payment success and failure.
- Generate a demo transaction reference after successful simulated payment.

**Note:** Online payment is a frontend demonstration only. No actual money is transferred.

### 🎫 Digital Order Token
- Generate a unique order ID.
- Generate a collection token.
- Display order confirmation details.
- Show collection date and time.
- Display payment and order status.
- Print the order receipt.

### 📋 Student Dashboard and Order History
- View previously placed orders.
- Check order details.
- View food quantities and total amounts.
- Review collection schedules.
- Check payment status.
- Access order confirmation information.

## 🔄 4. Working Process

The application follows a simple four-step ordering process:

**Step 1: Register / Log In**

Students create an account using their student details or log in using their existing demo account.

**Step 2: Explore the Food Menu**

Students browse different food categories, search for food items, check prices, and select their favourite dishes.

**Step 3: Add to Basket and Pre-Book**

Students add food items to the basket, select quantities, proceed to checkout, and choose their preferred collection date and time.

**Step 4: Payment and Food Collection**

Students select Pay at Canteen or the simulated online payment option. After successful order placement, the system generates an order confirmation and collection token.

Students can show the token at the canteen to identify their order.

## 🛠️ 5. Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the web application |
| CSS3 | Styling, layouts, and responsive design |
| JavaScript | Application functionality and interactions |
| LocalStorage | Browser-based storage of demo accounts, baskets, and orders |
| Google Fonts | Typography and visual appearance |
| Font Awesome | Icons and visual elements |
| Git | Version control |
| GitHub | Source code hosting |
| GitHub Pages | Application deployment |

### Frontend

The frontend is developed using HTML, CSS, and Vanilla JavaScript. It provides the user interface and handles student registration, login, menu browsing, basket operations, checkout, and order confirmation.

### Backend

A server-side backend has not yet been implemented. The current project operates as a browser-based frontend prototype.

### Database

The current version uses browser LocalStorage for demonstration purposes. It stores student demo records, session information, basket data, checkout details, and order history.

## 📂 6. Project Structure

```text
Smart-Campus-Food-Ordering-System/
│
├── frontend/
│   │
│   ├── index.html
│   ├── register.html
│   ├── login.html
│   │
│   ├── student/
│   │   ├── menu.html
│   │   ├── checkout.html
│   │   ├── payment.html
│   │   ├── order-confirmation.html
│   │   └── dashboard.html
│   │
│   ├── css/
│   │   ├── global.css
│   │   ├── student.css
│   │   ├── menu.css
│   │   ├── student-flow.css
│   │   └── splash.css
│   │
│   ├── js/
│   │   ├── menu.js
│   │   ├── student-auth.js
│   │   ├── checkout.js
│   │   ├── payment.js
│   │   ├── order-confirmation.js
│   │   ├── dashboard.js
│   │   ├── canteengo-data.js
│   │   └── splash.js
│   │
│   └── assets/
│
├── .gitignore
├── PROJECT_STATUS.md
└── README.md
```

## ⚙️ 7. Installation and Setup

Follow these steps to run the project on your local computer.

**Step 1: Clone the Repository**

```bash
git clone https://github.com/rakeshreddy5449-blip/Smart-Campus-Food-Ordering-System.git
```

**Step 2: Open the Project**

```bash
cd Smart-Campus-Food-Ordering-System
```

**Step 3: Open in Visual Studio Code**

```bash
code .
```

**Step 4: Run the Application**

- Open the `frontend` folder.
- Locate `index.html`.
- Right-click the file.
- Select **Open with Live Server**.

Alternatively, open `frontend/index.html` directly in your browser.

**Step 5: Explore the Application**

Register a demo student account, log in, browse the food menu, add food items to the basket, select a collection time, and complete the checkout process.

## 🌐 8. Project Links

| Resource | Link |
|---|---|
| Live Application | https://rakeshreddy5449-blip.github.io/Smart-Campus-Food-Ordering-System/ |
| GitHub Repository | https://github.com/rakeshreddy5449-blip/Smart-Campus-Food-Ordering-System |

## 🧪 9. Testing

The following functionalities have been covered through manual browser testing:

- Student registration and login.
- Registration form validation.
- Duplicate student details checking.
- Food menu browsing and searching.
- Food category and dietary filtering.
- Shopping basket operations.
- Quantity modification and price calculation.
- Checkout and collection scheduling.
- Pay at Canteen order placement.
- Simulated online payment success and failure.
- Order ID and collection token generation.
- Order confirmation and receipt printing.
- Student dashboard and order history.
- Browser refresh and LocalStorage persistence.
- Responsive layout checks.

## 🔐 10. Limitations and Future Enhancements

The current version is an academic frontend prototype. The following features can be added in future versions.

1. **Backend Integration:** Develop a secure backend using Node.js, Express.js, or another suitable server-side technology.
2. **Database Integration:** Integrate MySQL or MongoDB to store student details, food items, and orders.
3. **Admin Dashboard:** Provide admin authentication, food menu management, order management, and order status updates.
4. **Canteen Staff Dashboard:** Allow canteen staff to view incoming orders and update their preparation status.
5. **Real-Time Order Tracking:** Allow students to track orders from placement to collection.
6. **Real Payment Gateway:** Integrate a secure payment gateway for actual UPI and card transactions.
7. **Notifications:** Send order confirmation and collection notifications.
8. **Security Improvements:** Implement server-side authentication, password hashing, authorisation, and secure data handling.
9. **Inventory Management:** Automatically update food availability based on stock.
10. **Mobile Application:** Develop an Android application for convenient campus food ordering.

## 🎓 11. Benefits of the Project

- Saves valuable student time.
- Reduces crowding at the canteen.
- Improves the food ordering experience.
- Provides convenient advance ordering.
- Reduces manual ordering activities.
- Makes food selection easier.
- Provides digital order identification.
- Helps demonstrate how digital technology can improve campus services.

## 🏁 12. Conclusion

The Smart Campus Canteen Pre-Booking System (CanteenGo) is designed to modernise the traditional university canteen ordering process through a simple and convenient web-based application.

It allows students to browse food items, place orders online, schedule collection times, select payment methods, and receive digital order tokens.

By reducing the need to stand in long queues, the system aims to make campus dining faster, easier, and more convenient.

This project demonstrates the practical application of HTML, CSS, JavaScript, and browser-based storage in developing a real-world campus-oriented web application.

In future development, backend integration, database connectivity, real payment processing, and admin functionality can transform this prototype into a complete campus canteen management solution.

---

## 👨‍💻 13. Project Information

**Project Name:** Smart Campus Canteen Pre-Booking System

**Application Name:** CanteenGo

**Institution:** SR University

**Project Type:** Web-Based Application

**Domain:** Web Development

**Deployment Platform:** GitHub Pages

**Repository:** Smart-Campus-Food-Ordering-System

---

<p align="center">
  <strong>🍔 CanteenGo – Your Campus. Your Canteen. Your Food.</strong>
</p>

<p align="center">
  Made for a smarter and more convenient campus experience.
</p>
