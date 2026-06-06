# UrbAcademy HR Management System (HRMS)

## 📌 Architecture Overview
This repository contains the core frontend and backend integration architecture for the UrbAcademy HR Management System (HRMS). Designed from inception to production, this platform provides secure, scalable employee management, real-time data retrieval, and strict Role-Based Access Control (RBAC).

## 🚀 Core Tech Stack
* **Framework:** Next.js 14 (React)
* **Language:** TypeScript
* **Database & Auth:** PostgreSQL & Supabase
* **UI & Styling:** Tailwind CSS, shadcn/ui, Framer Motion
* **Deployment & Edge:** Vercel, Cloudflare

## ✨ Key Features
* **Role-Based Access Control (RBAC):** Strict security policies utilizing Supabase Auth to isolate Admin, HR, and Standard Employee routing and data access.
* **Relational Data Integrity:** Normalized PostgreSQL database schemas handling employees, departments, and attendance logs.
* **Premium UI/UX:** Responsive, mobile-first layouts featuring Glassmorphism design and GPU-accelerated page transitions via Framer Motion.
* **Zero Layout Shift:** Highly optimized component-driven architecture to ensure peak Web Vitals and zero cumulative layout shift across all breakpoints.
* **Automated CI/CD:** Seamless edge deployment pipelines configured through Vercel.

## ⚙️ Local Development Setup

Follow these steps to run the HRMS architecture on your local machine.

### Prerequisites
* Node.js 18+ installed
* A Supabase project setup for database and authentication
* Git

### Installation

1. **Clone the repository:**
   ```bash
   git clone <YOUR_GIT_URL>
