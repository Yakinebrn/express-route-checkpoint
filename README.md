# Express Route Checkpoint

## 📌 Project Description
This project is a simple **web application with three pages** built using **Node.js and Express**.  
The goal was to practice routing, middleware, and static file serving.

---

## 🎯 Requirements
According to the checkpoint instructions, the application had to:
1. Contain **three pages**:
   - Home
   - Our Services
   - Contact Us
2. Each page must include a **navigation bar** with links to the three pages.
3. The web application must be **only available during working hours**:
   - Monday to Friday
   - From 9 AM to 5 PM
4. Use **Express** to create the server and handle routes.
5. Create a **custom middleware** to verify the time of the request.
6. Style the pages with **CSS**.
7. (Optional) Use a **template engine** (not used here, only plain HTML + CSS).

---

## ✅ What We Implemented
- An **Express server** (`server.js`) with routes for:
  - `/` → `home.html`
  - `/services` → `services.html`
  - `/contact` → `contact.html`
- A **middleware** (`workingHoursMiddleware`) that checks the day and time:
  - If the request is during working hours → allow access.
  - Otherwise → show a message: *"Sorry, the website is only available from Monday to Friday, 9 AM to 5 PM."*
- **Static files setup**:
  - CSS is served from the `public/` folder.
  - HTML files are stored in the `views/` folder.
- **Styling**: pages are styled with CSS (with a girly/dark pink navbar style and clean content formatting).
