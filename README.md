# 🛍️ Trendy Shop

Modern full-stack e-commerce application built with Next.js, Node.js, Prisma and PostgreSQL.

---

# ✨ Features

- 🔐 JWT Authentication
- 👤 Admin & User Roles
- 🛒 Shopping Cart System
- ❤️ Favorites / Wishlist
- 📦 Order Management
- 🔍 Product Search & Filtering
- 🧾 Admin Dashboard
- 📱 Responsive Design
- ⚡ Full-stack Architecture
- 🗄️ Prisma ORM + PostgreSQL

---

# 🧰 Tech Stack

## Frontend
- Next.js
- React
- TypeScript
- TailwindCSS

## Backend
- Node.js
- Express.js
- Prisma ORM
- PostgreSQL

## Authentication
- JWT (JSON Web Token)

---

# 📂 Project Structure

```bash
/client
  ├── components
  ├── pages
  ├── services
  ├── hooks
  ├── store
  └── styles

/server
  ├── controllers
  ├── routes
  ├── middleware
  ├── prisma
  ├── utils
  └── config
```

---

# 🚀 Installation

## 1) Clone Project

```bash
git clone https://github.com/USERNAME/trendy-shop.git
cd trendy-shop
```

---

# ⚙️ Environment Setup

Create a `.env` file in the root directory:

```env
# Database
DATABASE_URL="postgresql://USER:PASSWORD@HOST:PORT/DATABASE"

# JWT
JWT_SECRET="your-secret-key"

# Backend Port
PORT=4000

# Frontend API URL
NEXT_PUBLIC_API_URL="http://localhost:4000"
```

---

# 📦 Install Dependencies

```bash
npm install
```

---

# 🗄️ Prisma Setup

## Generate Prisma Client

```bash
npm run prisma:generate
```

## Run Database Migration

```bash
npm run prisma:migrate
```

## Optional: Seed Database

```bash
npm run prisma:seed
```

---

# ▶️ Run Project

## Full-stack (Recommended)

Runs frontend and backend together:

```bash
npm run dev:full
```

---

## Run Separately

### Backend

```bash
npm run dev:server
```

### Frontend

```bash
npm run dev
```

---

# 🌐 Local URLs

| Service | URL |
|---|---|
| Frontend | http://localhost:3000 |
| Backend | http://localhost:4000 |

---

# 👤 Admin Login

Use the following credentials to access the admin panel:

```txt
Email: admin@test.com
Password: 123456
```

⚠️ Important:
Please change admin credentials in production.

---

# 🔐 Authentication

- JWT-based authentication
- Protected routes
- Role-based authorization
- Persistent login sessions

---

# 📡 API Endpoints

## Auth

| Method | Endpoint | Description |
|---|---|---|
| POST | `/auth/register` | Register user |
| POST | `/auth/login` | Login user |

---

## Products

| Method | Endpoint |
|---|---|
| GET | `/products` |
| GET | `/products?brand=nike` |
| GET | `/products?search=keyword` |
| POST | `/products` |
| PUT | `/products/:id` |
| DELETE | `/products/:id` |

---

## Orders

| Method | Endpoint |
|---|---|
| GET | `/orders` |
| POST | `/orders` |

---

## Cart

| Method | Endpoint |
|---|---|
| GET | `/cart` |
| POST | `/cart` |
| DELETE | `/cart/:id` |

---

## Favorites

| Method | Endpoint |
|---|---|
| GET | `/favorites` |
| POST | `/favorites` |
| DELETE | `/favorites/:id` |

---

# 🧪 Available Scripts

```json
"scripts": {
  "dev": "next dev",
  "dev:server": "nodemon server/index.js",
  "dev:full": "concurrently \"npm run dev\" \"npm run dev:server\"",
  "build": "next build",
  "start": "next start",
  "prisma:generate": "prisma generate",
  "prisma:migrate": "prisma migrate dev",
  "prisma:seed": "prisma db seed"
}
```

---

# 🚀 Deployment

## Recommended Services

| Service | Recommendation |
|---|---|
| Frontend | Vercel |
| Backend | Railway / Render |
| Database | Neon PostgreSQL |

---

# ✅ Production Checklist

- [ ] Change JWT secret
- [ ] Change admin credentials
- [ ] Configure CORS
- [ ] Setup production database
- [ ] Run Prisma migrations
- [ ] Remove test/seed data

---

# 📸 Screenshots

Add your project screenshots here.

Example:

```md
![Home Page](./screenshots/home.png)
![Admin Panel](./screenshots/admin.png)
```

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

Developed by Ipek Arlı.
