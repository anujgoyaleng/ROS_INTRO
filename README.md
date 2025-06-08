# 🌿 ROS (Republic of Subjiwala) — Website

**Connecting local vegetable vendors to consumers through technology.**

---

## 📌 Project Overview

**ROS (Republic of Subjiwala)** is a web platform modernizing the traditional vegetable market by digitally connecting vendors, consumers, and investors. Built with **Next.js**, the platform offers seamless onboarding for vendors, easy shopping for consumers, and clear value for investors.

This repository contains the source code and content plan for the ROS website.

---

## 📁 Folder Structure

```bash
/src
│
├── pages/                    # Route-based pages
│   ├── index.tsx            # Homepage
│   ├── vendors.tsx          # Vendor onboarding page
│   ├── investors.tsx        # Investor info page
│   ├── consumers.tsx        # Consumer landing page
│   ├── blog.tsx             # News & articles
│   └── contact.tsx          # Contact & support
│
├── components/              # Reusable UI and section components
│   ├── home/                # Homepage sections (hero, services, etc.)
│   ├── vendors/             # Vendor page components
│   ├── investors/           # Investor page components
│   ├── consumers/           # Consumer page components
│   ├── blog/                # Blog/news sections
│   ├── contact/             # Contact & support components
│   ├── layout/              # Layout components (Header, Footer)
│   └── common/              # Common UI elements (Button, Card, etc.)
│
├── styles/                  # Global and modular styles
│   ├── globals.css
│   └── variables.scss
│
├── hooks/                   # Custom React hooks
│   └── useForm.ts
│
├── context/                 # Global state with React context
│   └── UserContext.tsx
│
├── utils/                   # Utility functions
│   ├── validateEmail.ts
│   └── formatDate.ts
│
├── services/                # API and data services
│   ├── vendorService.ts
│   ├── investorService.ts
│   ├── blogService.ts
│   └── contactService.ts
│
├── lib/                     # Configuration and libraries
│   ├── api.ts
│   └── config.ts
│
└── types/                   # TypeScript types and interfaces
    ├── vendor.d.ts
    ├── investor.d.ts
    ├── consumer.d.ts
    └── blog.d.ts
```

## ⚙️ Workflow

### 1. Development
All development happens inside the /src folder.

Each route (page) is defined in /pages.

UI sections are built as components inside /components.

### 2. Component Design
Modular and reusable components are used.

Each component is scoped by page type (e.g., /components/vendors).

### 3. Styling
Global styles go into globals.css.

Component-level styles use .module.css or .scss for modularity.

### 4. API & Data
All data fetching logic is abstracted inside /services.

Uses fetch or axios for REST APIs.

### 5. State Management
React Context API is used for global state (/context).

Hooks are used for local or reusable logic (/hooks).

### 6. Typescript & Type Safety
Strongly typed using .d.ts files inside /types.


