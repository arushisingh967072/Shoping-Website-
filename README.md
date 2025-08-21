# E-Commerce Clothing Website

🚀 **Overview**  
An online clothing store built with the MERN stack. This platform allows users to browse, filter, and purchase clothing items while providing admins with full control over products and orders.

**Key highlights:**  
- Full Frontend, Backend, and Admin Panel  
- Secure user authentication and admin login  
- Smooth shopping experience with Razorpay and Cash on Delivery options  

---

## What Makes This Project Unique?

- 🛒 Seamless shopping experience – browse, filter, and purchase clothing easily  
- 👕 Product filtering & sorting – Categories (Men, Women, Kids), Types (Topwear, Bottomwear, Winterwear), Price and relevance sorting  
- 📦 Order management – users can track purchases; admins can manage order history  
- 🔐 Secure authentication – JWT-based login for users and admins  
- 💻 Admin panel – add, update, and remove products, view orders, and manage inventory  

---

## Features

**Frontend:**  
- Navigation tabs: Home, Collection, About, Contact, Footer  
- Add products to cart and proceed with Razorpay or Cash on Delivery  
- Filter products by category, type, and sorting  
- Search bar for finding products quickly  
- User authentication (Login/Create Account)  
- Track and view order history  

**Backend:**  
- Stores users, admins, products, and orders  
- Secure JWT authentication with middleware protection  
- Admin can delete or update customer orders  
- Centralized database management  
- Handles all API requests for frontend and admin  

**Admin Panel:**  
- Secure login for admin only  
- Add new products  
- List and manage existing products  
- View and manage all orders  
- Control over product inventory and order history  

---

## 🛠 Tech Stack

- **Frontend:** React.js  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB  
- **Styling:** Tailwind CSS  
- **Authentication:** JWT  

---

## 🛠 Installation

**Clone the repository:**  
```bash
git clone https://github.com/arushisingh967072/Shoping-Website-.git

# Backend Setup:
cd .\backend\
npm install
npm run start

# Admin Panel Setup:
cd ..\admin\
npm install
npm run dev

# Frontend Setup:
cd ..\frontend\
npm install
npm run dev
