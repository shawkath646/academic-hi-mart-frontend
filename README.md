<!-- HEADER SECTION -->
<div align="center">

# HiMart — Frontend Web Application

**Modern single-page e-commerce shopping experience engineered with React 19, Tailwind CSS v4, and Vite.**

<!-- BADGES -->
[![Platform](https://img.shields.io/badge/Platform-Full--Stack%20Web-0A66C2?style=flat-square)](#)
[![Author](https://img.shields.io/badge/Author-Shawkat%20Hossain%20Maruf-black?style=flat-square)](https://shawkath646.dev)
[![Ecosystem](https://img.shields.io/badge/Ecosystem-clouburstlab-2563EB?style=flat-square)](https://clouburstlab.com)
[![Course](https://img.shields.io/badge/Course-Web%20Programming-orange?style=flat-square)](#)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#-license)
[![React](https://img.shields.io/badge/React-19.1.0-61DAFB?style=flat-square&logo=react&logoColor=black)](#)

</div>

---

### 📋 Project Overview

| Property | Details |
| :--- | :--- |
| **Author** | [Shawkat Hossain Maruf](https://shawkath646.dev) |
| **Course** | Web Programming |
| **Platform** | Modern Web (SPA / Responsive) |
| **Period / Timeline** | Spring 2025 (Mar 2025 – May 2025) |
| **Status** | Completed / Academic Project |
| **Primary Stack** | React 19, Tailwind CSS v4, React Router, Vite, Framer Motion |

---

> [!IMPORTANT]
> **Academic Coursework Notice**  
> This project serves as the client-side single-page application (SPA) for the **HiMart** e-commerce platform, built as comprehensive coursework for the **Web Programming** course. It pairs with the [`academic-hi-mart-backend`](https://github.com/shawkath646/academic-hi-mart-backend) REST API service.

---

## 🎯 Purpose & Problem Statement

### Why It Exists
Traditional multi-page storefronts suffer from frequent full-page reloads, sluggish cart updates, and poor mobile responsiveness. HiMart Frontend was developed to deliver an app-like e-commerce shopping interface with instantaneous page transitions, dynamic state persistence, and a polished seller management console.

### What It Solves
- **Instantaneous UI Transitions:** Single Page Application (SPA) routing powered by React Router v7 eliminates blank page flickers during navigation.
- **Reactive Shopping Cart:** Client-side cart state synchronized with backend storage, complete with quantity adjustment and pricing breakdown.
- **Vendor / Seller Management Console:** Dedicated merchant dashboard for uploading product images, setting inventory levels, and managing orders.

---

## 💡 Key Insights & Architecture

- **Component-Driven UI:** Modular component architecture separating layout shells, navigation, product cards, checkout flows, and seller controls.
- **Styling with Tailwind CSS v4:** Leverages utility-first CSS for responsive layouts across mobile, tablet, and widescreen desktop monitors.
- **Fluid Micro-Interactions:** Smooth page transitions, cart drawer slide-outs, and modal dialogs powered by Framer Motion.
- **Debounced Search & Filtering:** Uses Lodash debounce to perform high-speed product catalog searches without saturating backend API endpoints.
- **Image Upload Integration:** Uses React Dropzone for drag-and-drop product picture uploads.

---

## 🛠️ Tech Stack & Dependencies

- **Framework:** React 19 (`19.1.0`)
- **Build Tool:** Vite 6 (`6.3.5`)
- **Styling:** Tailwind CSS v4 (`@tailwindcss/vite`)
- **Routing:** React Router (`7.6.1`)
- **Animation:** Framer Motion (`12.12.2`)
- **HTTP Client:** Axios (`1.9.0`)
- **Utilities:** Headless UI, React Dropzone, Chart.js

---

## 🚀 Getting Started

### Prerequisites
Make sure you have installed:
- `Node.js >= 18.x`
- `npm` or `pnpm`

### Installation & Development

```bash
# 1. Clone the repository
git clone https://github.com/shawkath646/academic-hi-mart-frontend.git
cd academic-hi-mart-frontend

# 2. Install dependencies
npm install

# 3. Configure environment variables
# Create a .env file and set your backend API URL:
# VITE_API_BASE_URL="http://localhost:5000"

# 4. Launch the local development server
npm run dev

# 5. Build for production
npm run build
```

---

## 🤝 Contributing & Support

This repository represents personal university coursework. Pull requests adding unrelated features are not accepted. Feedback and issues can be submitted on the [Issue Tracker](https://github.com/shawkath646/academic-hi-mart-frontend/issues).

---

## 📄 License

Distributed under the [MIT License](LICENSE). See `LICENSE` for more information.

---

<!-- BRANDING FOOTER -->
<div align="center">
  <sub>Engineered by</sub><br/>
  <strong><a href="https://shawkath646.dev">Shawkat Hossain Maruf</a></strong>
  <br/><br/>
  <sub>A product of</sub><br/>
  <a href="https://clouburstlab.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://assets.clouburstlab.com/branding/icon_dark.png">
      <source media="(prefers-color-scheme: light)" srcset="https://assets.clouburstlab.com/branding/icon_light.png">
      <img alt="clouburstlab" src="https://assets.clouburstlab.com/branding/icon_light.png" width="230">
    </picture>
  </a>
</div>
