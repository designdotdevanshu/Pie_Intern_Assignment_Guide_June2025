# 📄 Pie Internship Assignment Guide

Welcome, and thank you for your interest in interning at **Pie**!

This short assignment is designed to assess your real-world skills across different roles, based on features we're building at Pie. Your task is to build/design a simple, focused version of our short-form video viewing experience - a scrollable vertical video feed with interactive overlays and contextual drawers.

- **📌 Final Submission Deadline:** 
🕛 June 4, 2025 — 11:59 PM IST
- **👤 Format:** Individual
- **🛠 Submission:**  
  * Developers: GitHub repository link with README & setup instructions
  * Designers: Figma link (or PDF export/screenshots) with notes
- **✅ Evaluation Criteria:**
  * Clarity and completeness
  * Code/design quality
  * Responsiveness and modularity
  * Creativity and attention to detail

---

## 🗂 Table of Contents

1. [Frontend Intern Assignment](#frontend-intern-assignment)
2. [Backend Intern Assignment](#backend-intern-assignment)
3. [Mobile Intern Assignment (React Native)](#mobile-intern-assignment-react-native)
4. [UI/UX Design Intern Assignment](#uiux-design-intern-assignment)

---

## 💻 Frontend Intern Assignment

### **Title:** Build a Fullscreen Vertical Video Feed with Interactive Overlay

### **Objective:**

Create a responsive, scrollable vertical feed of short videos. Each video is displayed one at a time (like a reel) with action overlays and a detail drawer that can be expanded to reveal more context.

### **Requirements:**

* Tech Stack: **React.js or Next.js**, **Tailwind CSS**
* Display one fullscreen video per view using **public dummy video URLs**
* Overlay UI on each video:

  * Creator’s name (e.g., “@alexdev”)
  * Action buttons (like, comment, share)
  * “More Info” button
* Clicking “More Info” should open a **drawer or modal** containing:

  * Video title and description
  * Thumbnail or reference image (can be placeholder)
* Must be **fully responsive** (works on mobile, tablet, desktop)
* Code should be modular, well-commented, and production-friendly

### **Bonus Points:**

* Smooth transition animations using **Framer Motion**
* Dummy interaction counters (e.g., Likes: 120, Comments: 15)

---

## 🧠 Backend Intern Assignment

### **Title:** Build an API to Store and Serve Short Video Content with Metadata

### **Objective:**

Create a backend service that supports uploading and retrieving video entries along with their creators and related contextual data (title, description, thumbnails, etc.).

### **Requirements:**

* Tech Stack: **Node.js**, **Prisma ORM**, **PostgreSQL**
* Define and implement the following models:

  * `User` (id, username, avatarUrl)
  * `Video` (id, title, description, videoUrl, userId, createdAt)
  * `MetaItem` (id, videoId, thumbnailUrl, label)
* Required REST API Endpoints:

  * `POST /videos` – Create a video with metadata
  * `GET /videos` – List all videos with creator and meta details
* Use hardcoded/dummy auth (e.g., a user object in code or basic header token)

### **Bonus Points:**

* Add an `Interaction` model to track likes, views, or comments
* Implement simple pagination for GET requests

---

## 📱 Mobile Intern Assignment (React Native)

### **Title:** Build a Scrollable Vertical Video Feed with Drawer for More Info

### **Objective:**

Build a React Native (or Expo) app that allows users to scroll through fullscreen short videos one by one, with an option to reveal extra context about each video.

### **Requirements:**

* Tech Stack: **React Native** (Expo is allowed)
* Features:

  * Show **fullscreen videos** in a vertically scrollable format
  * Display overlays: creator’s name, action buttons (e.g., like/share)
  * “More Info” button opens a **bottom drawer**
* Drawer Content:

  * Video title
  * Optional thumbnail/image
  * Short description text

### **Bonus Points:**

* Add animations for drawer open/close
* Floating action button showing interaction count (optional)

---

## 🎨 UI/UX Design Intern Assignment

### **Title:** Design a Fullscreen Short Video Experience with Contextual Drawer

### **Objective:**

Design a clean, mobile-first interface that allows users to scroll through fullscreen short videos and interact with them. Each video should include the option to view extra information in an elegant, expandable drawer.

### **Requirements:**

* Tools: **Figma**, **Adobe XD**, or similar
* Screens to Design:

  1. **Video Viewing Screen**

     * Fullscreen video layout
     * Creator name
     * Action buttons (like, comment, share, info)
  2. **Info Drawer**

     * Title, description, and thumbnail or image
* Focus on:

  * Mobile-first layout (iOS/Android)
  * Visual hierarchy and button placements
  * Smooth, intuitive user interaction

### **Bonus Points:**

* Show microinteractions or animation transitions between screens
* Include a dark mode variation
