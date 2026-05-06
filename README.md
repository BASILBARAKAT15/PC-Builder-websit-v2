# 💻 PC Builder Website v2
> A high-performance, interactive web application for custom PC configuration and compatibility management.

[![GitHub repo size](https://img.shields.io/github/repo-size/BASILBARAKAT15/PC-Builder-websit-v2?style=for-the-badge&color=blue)](https://github.com/BASILBARAKAT15/PC-Builder-websit-v2)
[![GitHub last commit](https://img.shields.io/github/last-commit/BASILBARAKAT15/PC-Builder-websit-v2?style=for-the-badge&color=green)](https://github.com/BASILBARAKAT15/PC-Builder-websit-v2)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📑 Overview
**PC Builder v2** is a refined solution for PC enthusiasts and builders. It simplifies the complex process of selecting computer parts by providing a structured, dynamic interface. Built with a focus on **User Experience (UX)** and **System Performance**, this version features a decoupled architecture for better scalability and maintenance.

---

## 🚀 Key Features

### 🧩 Intelligent Configuration
* **Dynamic Selection:** Seamlessly add or swap components (CPU, GPU, RAM) with real-time UI updates.
* **Smart Filtering:** Browse components categorized by performance tier and technical compatibility.
* **Persistent Builds:** Tracks your current configuration across sessions using local state management.

### 📦 Component Management
* **Detailed Catalog:** High-resolution images and comprehensive specification sheets for every part.
* **Live Pricing Overview:** Integrated price tracking to help users stay within budget.

### ⚡ Technical Excellence
* **Responsive Design:** Fully optimized for Mobile, Tablet, and Desktop environments.
* **Zero-Lag Navigation:** High-speed transitions between the component catalog and the building dashboard.

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | [Next.js](https://nextjs.org/) / [React.js](https://reactjs.org/) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) |
| **State Management** | React Context API / Hooks |
| **Backend** | [Node.js](https://nodejs.org/) & API Routes |
| **AI Engine** | [Groq Cloud API](https://groq.com/) (Llama-3 Integration) |

---

## 📂 Architecture Preview

```text
src/
├── components/     # Atomic Design: Reusable UI components (Buttons, Cards, Modals)
├── hooks/          # Custom React hooks for business and data logic
├── layouts/        # Page wrapper components for consistent branding
├── pages/          # File-based routing and page entry points
├── styles/         # Global Tailwind and CSS configurations
└── utils/          # Formatting logic, validators, and helper constants
