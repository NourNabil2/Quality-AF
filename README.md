# 🏭 Quality AF – Manufacturing Management System

![Header Image](assets/header.png)  
*A complete cross-platform system for managing supply orders, tracking workflow, and monitoring payment collection.*

---

## 📱 Overview

**Quality AF** is a **Flutter**-based system built for both **mobile** and **desktop** platforms.  
It’s designed to help manufacturing facilities manage and track supply orders from start to finish — from order creation to delivery and payment collection — using a clean **MVVM architecture** with **Cubit state management** and **Supabase** as the backend.

---

## ⚙️ Features

-  **Order Management** – Create, assign, and track production orders in real time.  
-  **Worker & Engineer Dashboard** – Each worker/engineer sees assigned tasks with deadlines.  
-  **Deadlines & Delivery Dates** – Set expected completion dates and track progress visually.  
-  **Collector Workflow** – Collectors record completed deliveries and payment receipts.  
-  **Notifications System** – Real-time notifications for new orders, updates, and payments.  
-  **Cross-Platform** – Runs smoothly on both mobile and desktop using a unified Flutter codebase.  
-  **Supabase Backend** – Authentication, database, and real-time updates handled via Supabase.  
-  **MVVM + Cubit** – Clean and maintainable architecture with clear separation of layers.

---

## 🧱 Architecture

The project follows the **MVVM (Model–View–ViewModel)** pattern with **Cubit** for state management.

lib/
│
├── core/ # Common utilities, themes, and constants
├── data/ # Data sources (Supabase integration, repositories)
├── models/ # Data models
├── view/ # UI layer (screens, widgets)
├── view_model/ # Cubits and business logic
└── main.dart # App entry point

The app follows the **MVVM pattern**:
- **Model** → Supabase data models  
- **View** → Flutter UI for mobile and desktop  
- **ViewModel** → Cubit classes managing business logic and state

---

## 🔔 Notifications

Integrated with Supabase and local notification services to:
- Notify workers when a new order is assigned.
- Notify collectors when a job is ready for delivery.
- Notify managers when payments are received.

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | Flutter (mobile + desktop) |
| State Management | Cubit (Bloc) |
| Architecture | MVVM |
| Backend | Supabase |
| Database | PostgreSQL (via Supabase) |
| Notifications | FireBase Realtime + Local Push |

---

## 🖼️ Screenshots

| Mobile | Desktop |
|--------|----------|
| ![Mobile 1](assets/mobile_1.png) | ![Desktop 1](assets/desktop_1.png) |
| ![Mobile 2](assets/mobile_2.png) | ![Desktop 2](assets/desktop_2.png) |

---

## 🚀 How It Works

1. The manager creates a new **order** request.
2. The system assigns it to **engineers and workers** based on workload.
3. Workers update progress → once completed → marked as **Ready for collection**.
4. **Collector** receives notification → picks up the order → collects payment.
5. **Payment** status updated and visible to management dashboard.

---

## 👨‍💻 Author

**Nour Nabil**  
📧 [nour60g@gmail.com]  
🔗 [LinkedIn](https://www.linkedin.com/nournabil0)

---

> _Quality AF – simplifying industrial workflows through smart, connected tools._

---

