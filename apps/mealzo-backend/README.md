# 🍽️ MealZo Backend

MealZo Backend is a scalable, modular, financial-grade REST API built with:

- Bun (runtime)
- Express.js (HTTP framework)
- TypeScript (strict mode)
- PostgreSQL (Neon)
- Redis (cache + queue)
- BullMQ (background jobs)

This backend powers:

- Authentication & RBAC
- Restaurant & menu management
- Order lifecycle management
- Payment processing
- Wallet ledger system
- Settlement engine
- Withdrawal system
- Admin controls

---

# 🏗️ Architecture Philosophy

The backend follows:

- Domain-based modular architecture
- Separation of business logic and HTTP layer
- Financial-safe ledger design
- Queue-based async processing
- Clean infrastructure separation

---

# 📦 Core Technologies

| Layer | Technology |
|--------|------------|
| Runtime | Bun |
| Framework | Express |
| Language | TypeScript |
| Database | PostgreSQL (Neon) |
| Cache | Redis |
| Queue | BullMQ |
| Validation | Zod |
| Auth | JWT |
| Hashing | bcrypt |
| Logger | Pino |

---

# 🔐 Security Features

- JWT-based authentication
- Role-based access control (RBAC)
- Zod request validation
- Centralized error handling
- Financial idempotency support
- Structured logging

---

# 💳 Financial Capabilities

- Payment processing integration
- Wallet ledger system
- Commission calculation engine
- Settlement processor
- Withdrawal queue system

---

# ⚙️ Runtime Commands

```bash
bun dev      # Development (watch mode)
bun start    # Production run
bun build    # Compile TypeScript