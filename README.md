# 🎬 ReelsPro

A modern video-sharing platform built with **Next.js**, **MongoDB**, **ImageKit**, and **NextAuth**. Users can create an account, log in, upload videos, and scroll through uploaded content in a clean, responsive interface.

## ✨ Features

* 🔐 User Authentication (Register & Login)
* 📹 Video Upload using ImageKit
* 🗄️ MongoDB Database Integration
* 📱 Responsive UI
* 🎥 Scroll and watch uploaded videos
* 👤 User-based access and session management
* ⚡ Built with the Next.js App Router

---

## 🛠️ Tech Stack

### Frontend

* Next.js 15
* React 19
* TypeScript
* Tailwind CSS
* DaisyUI

### Backend

* Next.js API Routes
* MongoDB
* Mongoose

### Authentication

* NextAuth.js
* JWT Sessions

### Media Storage

* ImageKit

---

## 📂 Project Features

### Authentication

* Register with email and password
* Secure login using NextAuth
* Session-based authentication

### Video Upload

* Upload videos directly to ImageKit
* Store video metadata in MongoDB
* Save:

  * Title
  * Description
  * Video URL
  * Thumbnail URL

### Feed

* Browse uploaded videos on the homepage
* Scroll and watch videos in a simple feed interface

---

## 📁 Project Structure

```bash
app/
├── api/
├── components/
├── login/
├── register/
├── upload/
├── layout.tsx
└── page.tsx

lib/
models/
public/
```

---

## ⚙️ Environment Variables

Create a `.env` file in the root directory.

```env
# Database
MONGODB_URI=

# Authentication
NEXTAUTH_SECRET=
NEXTAUTH_URL=http://localhost:3000

# ImageKit
IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_PUBLIC_KEY=
NEXT_PUBLIC_URL_ENDPOINT=
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/alphasaurabh/ReelsPro-.git
cd ReelsPro-
```

### Install dependencies

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

## 📸 Application Flow

1. Register a new account.
2. Login to your account.
3. Upload videos from the Upload page.
4. Videos are stored using ImageKit and metadata is saved in MongoDB.
5. View and scroll through uploaded videos on the homepage.

---

## 🔮 Future Improvements

* Like and comment system
* User profiles
* Video categories
* Search functionality
* Follow system
* Admin dashboard
* Video analytics
* Infinite scrolling feed

---

## 👨‍💻 Author

**Saurabh Chandravanshi**

GitHub: https://github.com/alphasaurabh

---

