# 🎉 EventHub - Premium Indian Event Management Platform

<div align="center">

![EventHub Banner](https://images.unsplash.com/photo-1540575467063-178a50c2df87?q=80&w=1200&h=400&fit=crop)

**A modern, full-featured event management platform showcasing Indian cultural and contemporary events**

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.0.8-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.3.6-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

### 🚀 [**LIVE DEMO**](https://event-hub-indian-event-management-p.vercel.app/) 🚀

[Features](#-features) • [Tech Stack](#-tech-stack) • [Getting Started](#-getting-started) • [Screenshots](#-screenshots)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Deployment](#-deployment)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)


---

## 🌟 Overview

**EventHub** is a production-ready event management platform built with modern web technologies. It features a stunning glassmorphism UI, smooth animations, and comprehensive event management tools. All events, locations, and content are focused on Indian culture and contemporary events.

### 🎯 Key Highlights

- **Modern UI/UX**: Glassmorphism design with smooth Framer Motion animations
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Indian Focus**: Features authentic Indian events with local venues and ₹ pricing
- **No Backend Required**: Uses local data storage for easy deployment
- **Production Ready**: Clean code, optimized performance, and SEO-friendly

---

## ✨ Features

### 🏠 **Home Page**
- Hero section with parallax effects and call-to-action buttons
- Featured upcoming events showcase
- Smooth scroll animations with AOS

### 📅 **Events Page**
- Interactive event cards with glassmorphism design
- Real-time search and category filtering
- 12+ curated Indian events (Diwali, Holi, IPL, Bollywood Night, Tech Summits, etc.)
- One-click event registration

### ➕ **Create Event**
- Comprehensive event creation form with validation
- Category selection (Cultural, Music, Sports, Business, Technology, etc.)
- Image URL integration
- Pricing and capacity management

### 📊 **Manage Events Dashboard**
- Analytics dashboard with interactive charts (Recharts)
- Key metrics: Total events, registrations, revenue (₹), attendance
- Edit and delete event functionality
- Registration tracking

### 📢 **Promotion Tools**
- Social media sharing (Facebook, Twitter, LinkedIn, Instagram)
- Email invitation system
- Shareable event links
- Lottie animations for engagement

### 📞 **Contact Page**
- Contact form with validation
- Embedded Google Maps (Hubli, Karnataka location)
- Social media links
- Company information

### 🔐 **Authentication**
- Login and registration pages
- User profile management
- LocalStorage-based authentication
- Social login UI (Google, Facebook)

---

## 🛠️ Tech Stack

### **Frontend**
- **React 18** - Modern UI library with hooks
- **Vite** - Next-generation build tool for blazing-fast development
- **React Router v6** - Client-side routing

### **Styling & Design**
- **Tailwind CSS** - Utility-first CSS framework
- **Custom Glassmorphism** - Frosted glass effects with backdrop-blur
- **Google Fonts** - Poppins, Montserrat, Raleway

### **Animations**
- **Framer Motion** - Production-ready motion library
- **AOS (Animate On Scroll)** - Scroll-triggered animations
- **Lottie** - High-quality animated illustrations

### **Data & State Management**
- **React Context API** - Global state management
- **LocalStorage** - Data persistence
- **Local JSON Data** - No backend/database required

### **Charts & Visualization**
- **Recharts** - Composable charting library

### **UI Components & Icons**
- **React Icons** - Comprehensive icon library
- **React Hot Toast** - Beautiful toast notifications
- **date-fns** - Modern date utility library

---

## 📁 Project Structure

```
event-organizer/
├── client/                      # React frontend application
│   ├── src/
│   │   ├── components/         # Reusable UI components
│   │   │   ├── Navbar.jsx
│   │   │   ├── Footer.jsx
│   │   │   ├── EventCard.jsx
│   │   │   ├── HeroSection.jsx
│   │   │   ├── DashboardCard.jsx
│   │   │   └── AnalyticsChart.jsx
│   │   ├── pages/              # Page components
│   │   │   ├── Home.jsx
│   │   │   ├── Events.jsx
│   │   │   ├── CreateEvent.jsx
│   │   │   ├── ManageEvents.jsx
│   │   │   ├── Promotion.jsx
│   │   │   ├── Contact.jsx
│   │   │   ├── Login.jsx
│   │   │   └── Register.jsx
│   │   ├── context/            # React Context
│   │   │   └── AuthContext.jsx
│   │   ├── data/               # Local data files
│   │   │   ├── eventsData.js
│   │   │   └── analyticsData.js
│   │   ├── App.jsx             # Root component
│   │   ├── main.jsx            # Entry point
│   │   └── index.css           # Global styles
│   ├── public/                 # Static assets
│   ├── package.json            # Dependencies
│   ├── vite.config.js          # Vite configuration
│   ├── tailwind.config.js      # Tailwind configuration
│   └── postcss.config.js       # PostCSS configuration
├── .gitignore                  # Git ignore rules
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Git**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/event-organizer.git
   cd event-organizer
   ```

2. **Install dependencies**
   ```bash
   cd client
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open in browser**
   ```
   http://localhost:5173
   ```

### Build for Production

```bash
cd client
npm run build
```

The optimized production build will be in the `client/dist/` folder.

### Preview Production Build

```bash
npm run preview
```

---

## 🌐 Deployment

### **Option 1: Vercel (Recommended)**

1. Push your code to GitHub
2. Visit [vercel.com](https://vercel.com) and sign up
3. Click "New Project" and import your repository
4. Configure:
   - **Framework Preset**: Vite
   - **Root Directory**: `client`
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
5. Click "Deploy"
6. Your site will be live in ~1 minute! 🚀

### **Option 2: Netlify**

1. Push to GitHub
2. Go to [netlify.com](https://netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Configure:
   - **Base directory**: `client`
   - **Build command**: `npm run build`
   - **Publish directory**: `client/dist`
5. Deploy

### **Option 3: Render**

1. Push to GitHub
2. Visit [render.com](https://render.com) and create account
3. Click "New +" → "Static Site"
4. Configure:
   - **Root Directory**: `client`
   - **Build Command**: `npm install && npm run build`
   - **Publish Directory**: `dist`
5. Deploy

### **Option 4: GitHub Pages**

1. Install gh-pages:
   ```bash
   cd client
   npm install --save-dev gh-pages
   ```

2. Update `vite.config.js`:
   ```javascript
   export default defineConfig({
     plugins: [react()],
     base: '/event-organizer/', // Your repo name
   })
   ```

3. Add to `package.json` scripts:
   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

4. Deploy:
   ```bash
   npm run deploy
   ```

---

## 📸 Screenshots

### Home Page
![Home Page](https://via.placeholder.com/800x400?text=Home+Page+Screenshot)

### Events Page
![Events Page](https://via.placeholder.com/800x400?text=Events+Page+Screenshot)

### Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Screenshot)

---

## 🇮🇳 Indian Events Featured

- **Diwali Celebration 2024** - India Gate, New Delhi
- **Bollywood Music Night** - Phoenix Marketcity, Mumbai
- **Startup India Summit** - Bangalore International Exhibition Centre
- **IPL Fan Fest 2024** - Wankhede Stadium, Mumbai
- **Tech Innovation Expo India** - Hyderabad International Convention Centre
- **Classical Dance Festival** - Kamani Auditorium, New Delhi
- **Holi Color Festival** - Jawaharlal Nehru Stadium, New Delhi
- **Sufi Music Evening** - Purana Qila, New Delhi
- **Yoga & Wellness Retreat** - Rishikesh, Uttarakhand
- **Street Food Festival** - Kingdom of Dreams, Gurgaon

All events feature Indian locations, pricing in ₹, and culturally relevant themes.

---

## 🎨 Design Features

### **Color Palette**
- **Primary**: Blue gradient (#0ea5e9 → #0284c7)
- **Accent**: Purple (#8b5cf6 → #7c3aed)
- **Background**: Dark gradient (slate-900 → purple-900)

### **Typography**
- **Headings**: Montserrat (bold, modern)
- **Body**: Poppins (clean, readable)
- **Subheadings**: Raleway (elegant)

### **UI Patterns**
- Glassmorphism cards with backdrop blur
- Smooth hover effects and transitions
- Parallax scrolling
- Responsive grid layouts
- Mobile-first design approach

---

## 🧪 Testing

Run the development server and test all features:

```bash
npm run dev
```

**Test Checklist:**
- [ ] All pages load correctly
- [ ] Navigation works smoothly
- [ ] Forms validate properly
- [ ] Responsive on mobile/tablet/desktop
- [ ] Animations are smooth
- [ ] No console errors

---

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---


## 👨‍💻 Author

**Your Name**

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)
- Portfolio: [yourwebsite.com](https://yourwebsite.com)

---

## 🙏 Acknowledgments

- [Unsplash](https://unsplash.com) - High-quality event images
- [React Icons](https://react-icons.github.io/react-icons/) - Icon library
- [Tailwind CSS](https://tailwindcss.com) - CSS framework
- [Framer Motion](https://www.framer.com/motion/) - Animation library

---

## 📞 Support

If you have any questions or need help, feel free to:

- Open an issue on GitHub
- Contact via email: your.email@example.com
- Connect on LinkedIn

---

<div align="center">

**⭐ If you like this project, please give it a star on GitHub! ⭐**

Made with ❤️ for amazing events in India

</div>
