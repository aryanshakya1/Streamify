# 🌍 Streamify — Language Exchange Platform

Streamify is a full-stack language exchange platform that connects users worldwide to practice new languages through **real-time chat and video calls**. It enables users to find partners, build connections, and improve speaking skills in an interactive environment.

---

## 🚀 Features

### 🔐 Authentication & Onboarding

* Secure user authentication using **JWT**
* Mandatory onboarding flow (profile completion required before access)
* Protected routes to ensure only authenticated users can use core features

### 👥 Social & Discovery

* Send and receive **friend requests**
* Real-time **notifications** for requests and updates
* Build a personalized network of language partners

### 💬 Real-Time Messaging

* Powered by **Stream API**
* Features include:

  * Reactions
  * Threaded conversations
  * Typing indicators
  * Instant message delivery
* Optimized for **low-latency communication**

### 📹 Video Calling

* One-click **video call invite links**
* Enables real-time speaking practice
* Seamless transition from chat → video interaction

### ⚡ Performance Optimizations

* Efficient server-state management using **TanStack Query**
* Custom React hooks for reusable logic
* Reduced redundant API calls through caching
* Improved UI responsiveness and reduced re-renders

---

## 🛠️ Tech Stack

### Frontend

* React.js
* TanStack Query
* Custom Hooks

### Backend

* Node.js
* Express.js
* MongoDB

### Real-Time & Communication

* Stream API (Chat + Video)

### Authentication

* JSON Web Tokens (JWT)

---

## 🧱 System Architecture

* **Client (React)** communicates with backend via REST APIs
* **Backend (Node.js/Express)** handles authentication, user data, and business logic
* **MongoDB** stores user profiles, relationships, and app data
* **Stream API** manages real-time messaging and video communication

---

## 📈 Scalability

* Designed to support:

  * **~100 concurrent real-time users**
  * **~1K monthly active users** (based on Stream API limits)
* Efficient state management reduces unnecessary network load

---

## 🎯 Use Case

Streamify solves a key problem in language learning:

> “Understanding a language is not enough — speaking practice is essential.”

By combining chat + video, users can:

* Practice conversational skills
* Learn from native speakers
* Build global connections

---

## 📂 Setup Instructions

```bash
# Clone the repository
git clone YOUR_GITHUB_LINK

# Install dependencies (frontend & backend)
npm install

# Start backend
npm run server

# Start frontend
npm run client
```

---

## ⭐ Final Note

Streamify is built with a focus on **real-time interaction, scalability, and user engagement**, making it a practical solution for modern language learning.
