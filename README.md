# InvoiceFlow – Modern Invoice Management SaaS

![Next.js](https://img.shields.io/badge/Next.js-15-black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue)
![Prisma](https://img.shields.io/badge/Prisma-ORM-green)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-blue)
![Auth.js](https://img.shields.io/badge/Auth.js-Authentication-purple)
![License](https://img.shields.io/badge/License-MIT-yellow)

A modern, full-stack invoice management platform built to streamline billing workflows for freelancers, agencies, and businesses. InvoiceFlow enables users to create, manage, send, and track invoices while automating client communication, payment reminders, PDF generation, and authentication.

Built using the latest web technologies including **Next.js App Router**, **Neon PostgreSQL**, **Prisma ORM**, **Auth.js**, **Mailtrap**, **Tailwind CSS**, and **Shadcn/UI**, the platform delivers a fast, secure, and scalable invoicing experience.

---

## 🚀 Features

### 📄 Invoice Management

* Create professional invoices
* Edit existing invoices
* Delete invoices
* Mark invoices as paid
* Track invoice status
* View invoice history

### 📧 Email Automation

* Send invoices directly to clients
* Beautiful responsive email templates
* Automated payment reminders
* Invoice delivery tracking
* Magic link authentication emails

### 📑 PDF Generation

* Dynamic PDF invoice creation
* Professional invoice layouts
* Download invoices instantly
* Printable invoice documents
* Real-time PDF generation

### 🔐 Authentication & Security

* Secure authentication with Auth.js
* Passwordless Magic Link Login
* Protected routes and dashboards
* Session management
* Secure server-side validation

### 📊 Analytics Dashboard

* Revenue overview
* Invoice statistics
* Payment tracking
* Monthly performance charts
* Interactive data visualization

### ⚡ Modern User Experience

* Responsive design
* Dark and light mode support
* Animated charts and dashboards
* Accessible UI components
* Fast page navigation

---

## 🏗️ Tech Stack

### Frontend

* Next.js App Router
* React
* TypeScript
* Tailwind CSS
* Shadcn/UI
* Framer Motion
* Recharts

### Backend

* Next.js Server Actions
* Route Handlers
* Prisma ORM
* PostgreSQL

### Database

* Neon PostgreSQL

### Authentication

* Auth.js
* Magic Link Authentication

### Email Services

* Mailtrap Email API
* Transactional Email Templates

### Validation

* Zod
* Conform

### Deployment

* Vercel

---

## 📁 Project Structure

```bash
invoiceflow/
│
├── app/
│   ├── dashboard/
│   ├── invoices/
│   ├── auth/
│   ├── settings/
│   └── api/
│
├── components/
│   ├── ui/
│   ├── dashboard/
│   ├── invoice/
│   └── email/
│
├── actions/
├── lib/
├── prisma/
├── hooks/
├── utils/
├── emails/
├── public/
│
├── middleware.ts
├── auth.ts
└── prisma.schema
```

---

## 💼 Core Functionality

### Create & Manage Invoices

Generate invoices with:

* Client information
* Invoice items
* Tax calculations
* Due dates
* Payment status tracking

### Send Client Invoices

Users can:

* Send invoices via email
* Share invoice links
* Download PDF versions
* Monitor delivery status

### Automated Payment Reminders

The platform automatically helps businesses:

* Reduce late payments
* Remind clients of outstanding invoices
* Improve cash flow management

### Revenue Tracking

Dashboard metrics include:

* Total revenue
* Paid invoices
* Outstanding balances
* Monthly earnings
* Invoice trends

---

## ⚙️ Environment Variables

Create a `.env` file:

```env
DATABASE_URL=

AUTH_SECRET=

AUTH_URL=

MAILTRAP_TOKEN=

MAILTRAP_ENDPOINT=

NEXT_PUBLIC_APP_URL=
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/invoiceflow.git
cd invoiceflow
```

### Install Dependencies

```bash
npm install
```

### Generate Prisma Client

```bash
npx prisma generate
```

### Run Database Migrations

```bash
npx prisma migrate dev
```

### Start Development Server

```bash
npm run dev
```

---

## 🔒 Security Features

* Passwordless authentication
* Magic link verification
* Secure session handling
* Server-side validation
* CSRF protection
* Protected API routes
* Environment variable isolation

---

## 📈 Performance Optimizations

* Server Components
* Server Actions
* Static and Dynamic Rendering
* Database Query Optimization
* Image Optimization
* Route-based Code Splitting

---

## 🌍 Deployment

Deploy seamlessly using Vercel:

```bash
npm run build
```

Production-ready deployment includes:

* Environment variable management
* PostgreSQL database integration
* Email service configuration
* Automatic CI/CD deployments

---

## 🎯 Future Improvements

* Multi-currency support
* Stripe payment integration
* Recurring invoices
* Client portal
* Team collaboration
* Expense tracking
* Subscription billing
* Advanced reporting

---

## 👨‍💻 Author

**Fouzia Oreen**

Full Stack MERN Developer | SaaS Builder | AI Solutions Developer

Portfolio: https://fouziaoreen.com

GitHub: https://github.com/Fouzia-Oreen

---

## ⭐ Support

If you found this project helpful, consider giving it a star on GitHub and sharing it with others.
