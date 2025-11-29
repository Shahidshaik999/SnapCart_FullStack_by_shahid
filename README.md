<h1 align="center">🛒 SnapCart – Full-Stack Grocery Delivery Platform</h1>

<p align="center">
A modern grocery delivery system with real-time order tracking, role-based access, and a seamless shopping experience.
</p>

---

## 📍 Overview
SnapCart is a production-ready full-stack web application supporting three user roles:
**Customer, Admin, and Delivery Partner**.

It features:
- Secure Authentication (Google + Email Login)
- Real-time Delivery Status Tracking (Socket.IO)
- Cloud-based Image Processing (Cloudinary)
- Live Maps for Address & Delivery (Leaflet + OpenStreetMap)

---

## 🚀 Tech Stack

| Category | Technologies |
|---------|--------------|
| Frontend | Next.js 16 (App Router), TypeScript, Tailwind CSS, Framer Motion |
| Backend | Next.js Server Actions, API Routes, Socket.IO |
| Database | MongoDB Atlas + Mongoose |
| Authentication | Auth.js (NextAuth), Google OAuth, bcryptjs |
| Maps | Leaflet + OpenStreetMap |
| Hosting | Vercel |
| Storage | Cloudinary |

---

## 🔐 Role-Based Access

### 👨‍🛍️ Customer
- Browse groceries by category  
- Add products to cart & checkout  
- Track order progress live  
- View order history

### 🧑‍💼 Admin
- Add/update/delete grocery items with cloud storage
- Manage orders & customers
- Daily earnings dashboard and analytics

### 🚴 Delivery Partner
- View assigned deliveries
- Live update status: **Pending → Out-for-Delivery → Delivered**
- Performance & earnings tracking

---

## ✨ Key Features

- 🔐 Auth.js based Login/Signup + Google OAuth
- 🛒 Cart + Dynamic Pricing + Address Validation
- 🚚 Realtime delivery updates with Socket.IO
- 🗺️ Live map → Location search + Pin drop address selection
- 🎨 Smooth animated UI (Framer Motion)
- 🌍 Fully responsive mobile-first design
- 📦 Cloudinary for image uploads

---

## 🖼️ Screenshots

<img width="468" height="411" alt="image" src="https://github.com/user-attachments/assets/82913029-6b56-44c6-bf39-8c32bfd9e40e" />
<img width="445" height="501" alt="image" src="https://github.com/user-attachments/assets/ea0ff9bc-4c23-4e30-b1c4-fd5b8db192de" />
<img width="428" height="412" alt="image" src="https://github.com/user-attachments/assets/972f8f7d-0809-439b-a579-ec72c24fe886" />
<img width="1853" height="987" alt="image" src="https://github.com/user-attachments/assets/8e495a8d-c204-4f69-8735-5ca59db98db5" />
<img width="1007" height="488" alt="image" src="https://github.com/user-attachments/assets/81a3bea7-c827-4dfa-bd52-552b21d85ea7" />
<img width="1623" height="952" alt="image" src="https://github.com/user-attachments/assets/330ce304-65d0-4815-aec5-6e714ffe317b" />
<img width="1038" height="713" alt="image" src="https://github.com/user-attachments/assets/6a2f7de0-4101-42ef-b613-fd11491ca68c" />
<img width="1857" height="967" alt="image" src="https://github.com/user-attachments/assets/f8976f0a-2f1d-4b8c-af8f-7b436c4a566c" />
<img width="1242" height="813" alt="image" src="https://github.com/user-attachments/assets/afc44585-045a-4874-9a63-0a96b20b38b8" />
<img width="892" height="658" alt="image" src="https://github.com/user-attachments/assets/0dfb42cf-c5f1-45d1-9ec3-2722bcb1e122" />


## 📡 Real-time Tracking Architecture

Socket.IO is used for:

Order status updates between admin ↔ delivery partner ↔ user

Live delivery timeline displayed on user dashboard

Leaflet + OpenStreetMap for:

Delivery route & pin updates

## 🚀 Deployment

This project is deployed using:

Vercel (Frontend + Serverless APIs)

MongoDB Atlas (Cloud DB)

## 📌 Future Enhancements

Online payments with Razorpay/Stripe (UI ready)

Delivery Partner live GPS tracking

Push notifications for updates

Discount coupons & subscription plans

## ✨ Author

👤 Shaik Shahid
📧 shahidshaik9898p@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/shaik-shahid-7a1897282/

🐙 GitHub: https://github.com/Shahidshaik999
