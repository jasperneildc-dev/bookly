# Bookly | Multi-Tenant Booking SaaS

**Bookly** is a high-performance, multi-tenant booking engine built with the MERN stack. It empowers businesses to launch their own branded, responsive booking storefronts in seconds using a single codebase and a centralized database.

![MERN Stack](https://img.shields.io/badge/Stack-MERN-blue)
![Responsive](https://img.shields.io/badge/Responsive-Yes-success)
![Platform](https://img.shields.io/badge/Platform-Web-orange)
![License](https://img.shields.io/badge/License-MIT-gray)

---

## 🚀 Overview

Bookly is designed to solve the complexity of scheduling for small to medium-sized businesses. Unlike traditional booking sites, Bookly uses a **Single-Project Multi-Tenant** strategy, allowing you to scale to thousands of clients without deploying new code for each one.

### 📱 One Codebase, Any Device
Built with a mobile-first philosophy. Whether your clients are on a desktop at the office or a smartphone on the go, the interface adapts perfectly using Tailwind CSS.

---

## 🛠 Tech Stack

- **Frontend:** React.js, Tailwind CSS, React Router
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Atlas)
- **Image Management:** Cloudinary
- **Deployment:** Vercel

---

## 🏗 System Architecture

Bookly identifies tenants based on the URL slug, enabling a personalized experience for every business.



1. **Dynamic Routing:** A user visits `bookly.com/mikes-barbershop`.
2. **Context Identification:** The React app parses the `businessSlug` from the URL.
3. **Data Fetching:** The API retrieves the specific branding, services, and availability for that business ID.
4. **Dynamic Theming:** The UI renders using the business's specific hex codes and logos.

---

## ✨ Key Features

- **Branded Storefronts:** Automatic theme application (colors, logos, hero images).
- **Admin Dashboard:** Self-service portal for business owners to update pricing, services, and photos.
- **Smart Scheduling:** Real-time availability checks to prevent double-booking.
- **Cloudinary Integration:** High-speed, optimized image delivery for service galleries.

---

## 🚦 Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB Atlas Account
- Cloudinary API Credentials

### Installation

1. **Clone the Repo**
   ```bash
   git clone [https://github.com/yourusername/bookly.git](https://github.com/yourusername/bookly.git)
   cd bookly
