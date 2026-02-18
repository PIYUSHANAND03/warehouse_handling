# 📦 invenTREE - Warehouse Management System

> **Where inventory grows in order**

A comprehensive warehouse management system built with React, TypeScript, Express, and MySQL. Features real-time updates, inventory tracking, order management, and advanced reporting.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)

## ✨ Features

- **📦 Inventory Management** - Track products, stock levels, and suppliers
- **📋 Order Processing** - Create and manage customer orders
- **🚚 Shipment Tracking** - Real-time delivery status updates
- **👥 Customer Management** - Customer profiles and order history
- **👷 Worker Management** - Staff tracking and performance
- **📊 Advanced Reporting** - Generate reports in multiple formats
- **⚡ Real-time Updates** - WebSocket integration
- **🔐 Role-Based Access** - Owner, Manager, Employee permissions
- **📱 Responsive Design** - Works on all devices
- **🌙 Dark Mode** - Multiple theme options

## 🛠️ Tech Stack

**Frontend:** React 18, TypeScript, Vite, TailwindCSS, Radix UI, TanStack Query  
**Backend:** Express.js, Prisma, MySQL, Socket.io, JWT  
**Tools:** pnpm, Vitest, Docker, Playwright

## 🚀 Quick Start

```bash
# Clone and install
git clone https://github.com/yourusername/inventory-management.git
cd inventory-management
pnpm install

# Setup database
pnpm db:up
pnpm prisma:generate
pnpm prisma:migrate
pnpm prisma:seed

# Start development
pnpm dev
```

Visit `http://localhost:8080`

## 📁 Project Structure

```
├── client/          # React frontend
├── server/          # Express backend
├── prisma/          # Database schema
├── shared/          # Shared types
└── public/          # Static assets
```

## 🔧 Environment

Create `.env` file:

```env
DATABASE_URL="mysql://user:password@localhost:3306/warehouse_db"
VITE_SOCKET_URL=http://localhost:3000
VITE_ENABLE_REALTIME=true
```

## 🧪 Commands

```bash
pnpm dev          # Start development server
pnpm build        # Build for production
pnpm test         # Run tests
pnpm typecheck    # Type checking
pnpm db:up        # Start MySQL with Docker
```

## 📊 Key Features

- **Dashboard:** Real-time statistics and quick actions
- **Inventory:** Product management with stock alerts
- **Orders:** Complete order lifecycle tracking
- **Reports:** Multi-format report generation
- **Authentication:** Secure login with role permissions

## 🐳 Docker

```bash
pnpm db:up        # Start database
docker-compose up -d  # Full stack deployment
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Open Pull Request

## 📝 License

MIT License - see [LICENSE](LICENSE) file for details

---

<div align="center">

**Made with ❤️ for efficient warehouse management**
