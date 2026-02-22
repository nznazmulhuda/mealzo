# 🍽️ Mealzo

Mealzo is a scalable, full-stack food delivery and commerce platform inspired by modern multi-vendor ecosystems.  
It is designed to support restaurants, customers, riders, and administrators within a unified, modular architecture.

This project is not a clone of any existing platform. It is an independently engineered system inspired by platforms like Foodpanda.

---

# 🚀 Vision

Mealzo aims to become a production-grade food marketplace system with:

- Multi-vendor restaurant onboarding
- Real-time order lifecycle management
- Wallet & internal transaction system
- Settlement & withdrawal engine
- Role-based access control
- Scalable backend architecture
- SaaS-ready foundation

---

# 📦 Monorepo Structure

```
.
├── apps/
│   ├── backend/          # Express + TypeScript API (Core business logic)
│   ├── web/              # Customer-facing frontend (future)
│   ├── admin/            # Admin dashboard (future)
│
├── packages/
│   ├── types/            # Shared TypeScript types
│   ├── config/           # Shared configurations
│   └── utils/            # Shared utilities
│
├── bun.lockb
├── package.json
└── README.md
```

---

# 🏗 System Architecture

Mealzo follows a **modular domain-driven backend architecture**.

Core backend modules include:

- Auth
- Users
- Restaurants
- Menu
- Cart
- Orders
- Payments
- Wallet
- Settlement
- Withdrawal
- Admin

Each module is isolated and scalable.

---

# 🛠 Tech Stack

## Runtime
- Bun

## Backend
- Express.js
- TypeScript
- PostgreSQL
- Redis
- JWT Authentication
- BullMQ (background jobs)
- Modular architecture

## Planned Extensions
- Real-time tracking (WebSocket)
- Payment gateway integration
- Analytics engine
- Microservice extraction (future scaling)

---

# ⚡ Key Features (Planned & In Progress)

### 👤 Customer
- Browse restaurants
- Add to cart
- Place orders
- Track order
- Wallet payments

### 🏪 Restaurant
- Manage menu
- Accept/reject orders
- Track earnings
- Request withdrawals

### 🚴 Rider
- Accept delivery tasks
- Order status updates
- Earnings tracking

### 🛠 Admin
- Full platform control
- Settlement management
- Withdrawal approval
- Fraud monitoring

---

# 🧠 Architectural Principles

- Clean separation of concerns
- Business-domain modularity
- Transaction-safe wallet logic
- Queue-based async processing
- Production-grade scalability
- SaaS monetization-ready

---

# 📥 Installation

Clone repository:

```bash
git clone <repository-url>
cd mealzo
```

Install dependencies:

```bash
bun install
```

---

# ▶️ Run Backend

```bash
cd apps/backend
bun run dev
```

---

# 🔐 Environment Configuration

Each app maintains its own `.env`.

Example:

```
apps/backend/.env
```

Never commit environment files.  
Use `.env.example` as reference.

---

# 🚀 Production Build

Backend:

```bash
bun build
bun start
```

---

# 📈 Future Roadmap

- Dockerized deployment
- CI/CD pipeline
- Cloud-native infrastructure
- Horizontal scaling
- Real-time dispatch optimization
- AI-based demand prediction

---

# 📄 License

Private & Proprietary  
© Nazmul Huda. All rights reserved.

---

# 👨‍💻 Maintained By

Nazmul Huda