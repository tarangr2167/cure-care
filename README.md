# Cure & Care: Full-Stack Pharmaceutical Platform

Cure & Care is a full-featured web application designed for pharmaceutical companies to showcase products, manage healthcare blogs, receive customer inquiries, and seamlessly handle backend administration—all with a modern, responsive design.

---

## 📜 What is Cure & Care?

Cure & Care is a modern web platform for pharmaceutical and nutraceutical businesses:
- **Showcases medical products** with images, details, and categories.
- **Publishes health news and blogs** for customer engagement.
- **Handles contact forms and subscriptions** for inquiries and updates.
- **Secure admin dashboard** for managing products, blogs, messages, and analytics.

---

## 🏗️ Project Structure
maid
flowchart TD
  subgraph Frontend
    F1(index.html)
    F2(src/App.jsx)
    F3(src/pages/)
    F4(src/component/)
    F5(public/)
  end
  subgraph Backend
    B1(server.js)
    B2(route/)
    B3(controller/)
    B4(model/)
    B5(Middleware/)
    B6(config/db.js)
  end
  subgraph Admin
    A1(src/AdminLayout.jsx)
    A2(src/pages/)
    A3(src/components/)
  end
  F1 --> F2 --> F3 --> F4
  B1 --> B2 --> B3 --> B4
  A1 --> A2 --> A3
  F2 --- B1
  A1 --- B1- **Frontend/**: React app for users—product listing, blogs, contact forms.
- **Backend/**: Node.js/Express REST API—secure business/data logic, file uploads, and DB connection.
- **Admin/**: React app for admin dashboard—CRUD operations, content moderation, analytics.

---

## 🚀 How to Run Locally

### 1️⃣ Clone the repository

git clone <your-repo-url>
cd cure-care### 2️⃣ Install dependencies

**For each folder: `Frontend/`, `Backend/`, and `Admin/`**
cd Frontend
npm install

cd ../Backend
npm install

cd ../Admin
npm install### 3️⃣ Set up environment

- Create a `.env` file in **Backend/** and configure MongoDB connection (see `config/db.js` for ref).
- For local dev, make sure MongoDB is running.

### 4️⃣ Start the applications

**Backend (API on port 5000 by default):**
cd Backend
npm start**Frontend:**
cd Frontend
npm run dev**Admin:**
cd Admin
npm run dev---

## 💻 Example Usage

- **User:** Browse products, search by category, read blogs/news, send messages via contact form.
- **Admin:** Login to dashboard, add/edit/delete products and blogs, monitor messages, view stats/charts.

---

## 🛠️ How It Works

- **Frontend:** React, Vite, Tailwind CSS/Bootstrap, Axios for API, animated and fully responsive.
- **Backend:** Node.js, Express, MongoDB, Mongoose, Multer (file uploads), Nodemailer (emailing), robust REST APIs.
- **Admin:** React dashboard for all content management and analytics.

---

## 📸 Screenshots

<img width="1917" height="966" alt="Screenshot 2026-01-05 104920" src="https://github.com/user-attachments/assets/5384d2e8-bda5-461c-9903-362fe3daf0fe" />

<img width="624" height="561" alt="Screenshot 2026-01-05 104935" src="https://github.com/user-attachments/assets/f9e61337-a9cf-47bf-a0e4-abc4f492ea32" />

<img width="1919" height="970" alt="Screenshot 2026-01-05 104947" src="https://github.com/user-attachments/assets/e57ac926-d041-4732-a225-30a88267062e" />

<img width="1919" height="974" alt="image" src="https://github.com/user-attachments/assets/b79c8930-a90f-4747-b275-0f5aa90b1f40" />



---

## 📊 Key Features

- Product catalog, blog engine, and newsletter subscriptions.
- Secure admin authentication with rich dashboard features.
- Real-time contact form, and automated email notifications.
- File upload (images/docs) for blogs and products.
- Built for scalability and top-tier user experience.

---
