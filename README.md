# 📚 Ideal Bookstore - Frontend

A modern React-based web application for college students to buy and sell textbooks within their campus community.  
**Built with ❤️ for Ideal Institute of Technology students**

---

## 🌟 Key Features

### 🏠 Landing Page
- Dynamic header with auto-hide/show on scroll
- Hero section with college-themed background
- Feature showcase (Affordable Prices, Buy & Sell, Campus Community, Wide Selection, Quick & Easy, Eco-Friendly)
- "How It Works" 3-step guide
- Smooth navigation with scroll-to-section
- Fully responsive design (mobile, tablet, desktop)

### 🔐 Authentication
- **Login**: Roll number-based (10-digit), password auth, demo credentials, error handling, auto-redirect
- **Registration**: Roll number, name, password confirmation, duplicate prevention, success feedback

### 🎯 Dashboard (Choose Page)
- Simple Buy/Sell interface
- Profile access & authentication guard
- Visual cards for intuitive actions

### 🛒 Buy Books
- Advanced search & filters (Book name, Regulation, Branch, Year)
- Book listings with price, condition, seller info, images
- Image zoom & modal view
- Excludes user's own books
- Loading and error states

### 🏷️ Sell Books
- Photo upload (up to 2 images, drag & drop, 5MB limit)
- Form fields: title, subject, category, regulation, condition, year, price, description
- Auto-populates seller roll number
- Form validation, success/error messages, auto-reset

### 👤 Profile Pages
- **My Profile**: Avatar, personal info, member since, books listed
  - Book management (delete listings, feedback, loading states)
- **Other Profiles**: Public view, seller info, all listed books

---

## 🛠 Technical Overview

### React & Architecture
- Built with **React 19**, React Router v7
- Functional components & hooks (useState, useEffect, useRef)
- Component-based modular design

### State Management
- Local storage for persistent auth state
- Controlled components for forms
- Loading states during async operations

### Authentication & Security
- JWT-like auth, route protection, session management

### API Integration
- REST API with Fetch, error handling, and CORS support

### UX & Performance
- Responsive mobile-first design (CSS Grid/Flexbox)
- Smooth animations, semantic HTML, ARIA labels
- Image optimization, lazy loading, code splitting
- Local storage caching to reduce API calls

---

## 🎨 Design System

- **Colors**: Blue gradient (primary), Green (success), Red (error), Orange (warning), Gray scale (neutral)
- **Typography**: System fonts, clear heading hierarchy
- **Components**: Buttons, forms, cards, modals with hover effects and transitions

---

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ & npm
- Backend API server running

### Installation
```bash
cd frontend
npm install
npm start
