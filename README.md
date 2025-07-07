## 📦 `online-pharmacy-backend-strapi`

This is the **Strapi-based backend** for the Online Pharmacy e-commerce platform. It provides a secure, API-driven interface for managing products, categories, brands, orders, and more.

The backend is designed to connect seamlessly with the React + Vite frontend: [`online-pharmacy-frontend-react`](https://github.com/amar-sheikh/online-pharmacy-frontend-react).

---

## 🚀 Tech Stack

* **Strapi v4** – Headless CMS for structured content management
* **Node.js** – Runtime environment
* **REST API** – API-based data exchange with frontend
* **PostgreSQL / SQLite** – Configurable database support
* **JWT Auth** – Secure API access

---

## 💊 Features Overview

### ✅ Product Management

* Add/edit/delete products
* Manage inventory, images, pricing
* Associate products with categories and brands

### 📂 Categories & Brands

* Create categories like *Natural Herb*, *Supplements*, etc.
* Manage pharmaceutical and herbal brands

### 🧾 Order Management

* View placed orders
* Update status (pending, shipped, completed)
* Store customer details (name, address, etc.)

### 🛡️ Auth & Permissions

* Role-based access for Admins, Authors, etc.
* API tokens for frontend communication

---

## 🔌 API Endpoints Overview

> All endpoints follow the REST pattern via `/api/*`

* `/api/products` – List all products
* `/api/products/:id` – Get a single product
* `/api/categories` – List all categories
* `/api/brands` – List all brands
* `/api/orders` – Create and manage orders

---

## 🌐 Frontend Integration

This backend is consumed by the **React frontend**:
🔗 [`online-pharmacy-frontend-react`](https://github.com/amar-sheikh/online-pharmacy-frontend-react)

The frontend uses the above APIs to:

* Fetch product listings
* Browse by category and brand
* Submit orders
* Display product details

---

## 📁 Project Setup

### 1. Clone the repo:

```bash
git clone git@github.com:amar-sheikh/online-pharmacy-backend-strapi.git
cd online-pharmacy-backend-strapi
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Set up environment variables:

Copy `.env.example` to `.env` and update as needed:

```bash
cp .env.example .env
```

### 4. Start Strapi:

```bash
npm run develop
```

> Visit the admin panel:
> [http://localhost:1337/admin](http://localhost:1337/admin)

