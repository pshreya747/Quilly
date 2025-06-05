# ✨ Quilly – A Real-Time Collaboration at Scale

## 📌 Project Overview

**Quilly** is a modern, collaborative document editing platform designed for teams to work together in real-time. Built using **Next.js**, **Liveblocks**, **Lexical**, and **Tailwind CSS**, it offers a seamless editing experience with multi-user presence, live comments, authentication, and more. Quilly showcases scalable real-time functionality, making it an ideal foundation for building production-grade collaborative tools.

---

### 📸 Project Screenshots
![Screenshot (67)](https://github.com/user-attachments/assets/7b4aec14-10a2-4c9d-b37e-1a50cb3a136a)
![Screenshot (68)](https://github.com/user-attachments/assets/45a133b8-0cdf-4277-98e3-6ce1558d4e5d)
![Screenshot (69)](https://github.com/user-attachments/assets/3804cc1f-4235-4cb4-9d5e-62b46f69f47b)
![Screenshot (70)](https://github.com/user-attachments/assets/dbce4c01-3904-4d3b-a8a7-f03506eff3d6)
![Screenshot (71)](https://github.com/user-attachments/assets/fe3ccf67-cfe0-42d8-ae43-3bdb6366766c)

---

## 🌟 Key Features

- 🔐 **Authentication with Clerk** (GitHub OAuth)
- 📝 **Real-Time Collaborative Editor** (Lexical + Liveblocks)
- 📄 **Create, Delete, and Manage Documents**
- 🗨️ **Inline and Threaded Comments**
- 👥 **Live Presence and Collaborator Avatars**
- 🔗 **Share Documents with Edit/View Permissions**
- 📬 **Email Notifications for Shares**
- 🔔 **Live Notifications for Comments & Activity**
- 🎨 **Clean, Responsive UI using TailwindCSS + ShadCN**
- 🚫 **Custom 404 and Error Handling Pages**

---

## ⚙️ Tech Stack

- **Next.js** – Fullstack React framework
- **TypeScript** – Strongly typed JavaScript
- **Clerk** – Authentication and user management
- **Liveblocks** – Real-time collaboration & presence
- **Lexical** – Modern extensible text editor
- **Tailwind CSS** – Utility-first responsive styling
- **ShadCN UI** – Component library for consistent UI
- **React Hot Toast** – Alerts and notifications
- **Lucide Icons** – Icon set for polished UI

---

## 📁 Environment Variables

Rename `.env.example` to `.env` and configure the following:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=your-liveblocks-public-key
LIVEBLOCKS_SECRET_KEY=your-liveblocks-secret-key
```


## 💻 Getting Started

### Prerequisites
- **Node.js** (v18 or higher)
- **Clerk Account** (Sign up at [Clerk](https://clerk.dev))
- **Liveblocks Account** ([Liveblocks Account](https://liveblocks.io))

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/pshreya747/quilly.git
   cd quilly
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Run the development server:**
   ```sh
   npm run dev
   ```

4. Open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

## 🌍 Deploying Quilly

### 1️⃣ Add Environment Variables
Add the `.env` variables to your hosting platform (e.g., **Vercel**, **Railway**, or **Heroku**).

### 2️⃣ Deploy
Deploy your app using your preferred method to make it live.

---


