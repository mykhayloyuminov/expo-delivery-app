<div align="center">

# Expo Delivery App

![Expo](https://img.shields.io/badge/Expo_52-000020?style=flat-square&logo=expo&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socket.io&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

**Full-featured food delivery mobile app with real-time order tracking, GPS navigation, and push notifications.**

</div>

---

## Overview

A complete food delivery ecosystem built as a Turborepo monorepo with multiple apps serving different user roles. Inspired by Glovo/Wolt architecture with real-time order lifecycle management.

## Apps

| App | Stack | Description |
|-----|-------|-------------|
| **Customer App** | Expo 52, React Native | Browse restaurants, place orders, track delivery |
| **Courier App** | Expo 52, React Native | Accept orders, GPS navigation, delivery confirmation |
| **Admin Dashboard** | Next.js 16 | Manage restaurants, orders, users, analytics |
| **Kitchen Display** | Next.js 16 | Real-time order queue for restaurant staff |
| **API Server** | NestJS, Prisma, PostgreSQL | REST API, WebSocket events, business logic |

## Key Features

- **Real-time tracking** via Socket.io for live order status and courier GPS
- **Push notifications** via Expo Notifications
- **Payment integration** with LiqPay + webhook confirmation
- **GPS navigation** with MapView and route visualization
- **Receipt printing** via ESC/POS thermal printers
- **Image uploads** via Cloudflare R2
- **Auth** with JWT + refresh tokens

## Tech Stack

**Mobile**: Expo 52, React Native, Zustand, TanStack Query, Expo Router, MapView

**Web**: Next.js 16, Tailwind CSS, Mantine UI, Recharts

**Backend**: NestJS, Prisma ORM, PostgreSQL, Socket.io, Bull queues

**Infra**: Docker, GitHub Actions, Cloudflare R2, Vercel

## License

MIT

---

<div align="center">
Built by <a href="https://github.com/mykhayloyuminov">Mykhaylo Yuminov</a> · <a href="https://complete-solution.eu">Complete Solution</a>
</div>
