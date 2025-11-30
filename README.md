# 💎 Crystal Shop API  
A RESTful backend for a magical crystal marketplace with categories, chakras, zodiac signs, intentions, reviews, and favorites.

---

## 📖 Overview

The Crystal Shop API allows users to browse magical crystals, filter by metaphysical properties, save favorites, create reviews, and explore categories such as chakras, zodiac signs, and intentions.

This project demonstrates:
- complex relational schemas  
- multi-filter search functionality  
- user authentication  
- e-commerce style architecture  
- organized development using Trello  

---

## 🗂 Tech Stack

- **Node.js**
- **Express.js**
- **PostgreSQL**
- **JWT Authentication**
- **REST API Architecture**

---

## 🧠 Features

- Full authentication system  
- CRUD operations for crystals and categories  
- Chakra, Zodiac, and Intention associations  
- Favorites system  
- User reviews  
- Search + filtering  
- Clean and scalable schema design  

---

## 🔄 Kanban Workflow (Trello)

This project uses Trello for Agile Kanban task management.

🔗 **Trello Board:** *(insert link here)*

### 📌 Screenshot  
*(Upload `kanban.png` and uncomment to show it)*

<!-- ![Kanban Board](./kanban.png) -->

---

## 🏗 Database Schema

Designed using dbdiagram.io with the following tables:

### Core Tables
- **Users**
- **Crystals**
- **Categories**
- **Chakras**
- **Zodiacs**
- **Intentions**

### Join Tables
- **CrystalCategories**
- **CrystalChakras**
- **CrystalZodiacs**
- **CrystalIntentions**

### User-Related
- **Favorites**
- **Reviews**

### 📌 Screenshot  
*(Upload `schema.png` and uncomment below)*

<!-- ![Database Schema](./schema.png) -->

---

---

## 🚀 Getting Started

### 1. Clone the repo

### 2. Install dependencies

### 3. Add environment variables  
Create `.env`:

### 4. Start development server  


---

# 🧪 API Endpoints

Below is the full endpoint list for the Crystal Shop API.

---

## 🔐 Authentication

### **POST /auth/signup**  
Register a new user.

### **POST /auth/login**  
Login and receive a JWT.

### **GET /auth/me**  
Return logged-in user.

### **POST /auth/logout**  
Client-side token removal.

---

## 💎 Crystals

### **GET /crystals**  
Return all crystals.

### **POST /crystals**  
Create a new crystal (admin/creator optional).

### **GET /crystals/:id**  
Return a single crystal.

### **PUT /crystals/:id**  
Update a crystal.

### **DELETE /crystals/:id**  
Remove a crystal.

---

## 🔎 Filtering Crystals

### **GET /crystals?category=protection**  
Filter by metaphysical category.

### **GET /crystals?chakra=heart**  
Filter by chakra.

### **GET /crystals?zodiac=aries**  
Filter by zodiac sign.

### **GET /crystals?intention=love**  
Filter by user intention.

---

## 🧿 Chakras

### **GET /chakras**
### **POST /chakras**
### **PUT /chakras/:id**
### **DELETE /chakras/:id**

---

## ♈ Zodiacs

### **GET /zodiacs**
### **POST /zodiacs**
### **PUT /zodiacs/:id**
### **DELETE /zodiacs/:id**

---

## 🌙 Intentions

### **GET /intentions**
### **POST /intentions**
### **PUT /intentions/:id**
### **DELETE /intentions/:id**

---

## 📂 Categories

### **GET /categories**
### **POST /categories**
### **PUT /categories/:id**
### **DELETE /categories/:id**

---

## ⭐ Reviews

### **POST /crystals/:id/reviews**
### **GET /crystals/:id/reviews**
### **PUT /reviews/:reviewId**
### **DELETE /reviews/:reviewId**

---

## ❤️ Favorites

### **GET /favorites**
### **POST /favorites/:crystalId**
### **DELETE /favorites/:crystalId**

---

## ❌ Error Handling

Uniform JSON error format:


---

## 🧩 Planning Files

Included in the repository:

- `schema.dbdiagram.txt`  
- `tasks.csv`  

---

## ✨ Author

**Michelle Liran Gepshtein**  
Digital Alchemist • Full-Stack Developer
 

## 📁 Project Structure

