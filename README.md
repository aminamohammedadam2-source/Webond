# 🌐 Webond – Connect Beyond
**Built by Yushat · React Platform · Version 1.0.0 · 2026**

A full-featured social media platform built with React.js — complete source code.

---

## 🚀 Quick Start (Run Locally)

### Prerequisites
- Node.js 16+ installed → https://nodejs.org
- npm (comes with Node.js)

### Steps
```bash
# 1. Unzip and enter the project folder
cd webond-react

# 2. Install all dependencies
npm install

# 3. Start the development server
npm start

# 4. Open your browser
# App runs at: http://localhost:3000
```

That's it! The app opens automatically in your browser.

---

## 📁 Project Structure
```
webond-react/
├── public/
│   └── index.html              ← HTML entry point
├── src/
│   ├── App.js                  ← Main router
│   ├── index.js                ← React entry point
│   ├── assets/css/
│   │   └── index.css           ← All styles (complete)
│   ├── context/
│   │   └── AppContext.js       ← Global state management
│   ├── utils/
│   │   ├── mockData.js         ← Sample data (posts, users, etc.)
│   │   └── helpers.js          ← Utility functions
│   ├── components/
│   │   ├── layout/             ← Layout, Sidebar, MobileNav
│   │   ├── feed/               ← StoriesBar, ComposeBox, PostCard, RightSidebar
│   │   ├── common/             ← Avatar, Modal, Toast
│   │   └── modals/             ← SearchOverlay, CreatePost, Story, Comments
│   └── pages/
│       ├── LoginPage.js        ← Sign in with email/Google/Apple/Facebook
│       ├── SignupPage.js       ← Create account
│       ├── HomePage.js         ← Feed with posts & stories
│       ├── ExplorePage.js      ← Search & trending
│       ├── ReelsPage.js        ← Short video feed
│       ├── MessagesPage.js     ← Full chat system
│       ├── NotificationsPage.js
│       ├── ProfilePage.js      ← User profile with edit
│       ├── GroupsPage.js
│       ├── EventsPage.js
│       └── SettingsPage.js     ← All settings panels
├── package.json
└── README.md
```

---

## 🌍 Deploy Online Free

### Netlify (Easiest)
```bash
npm run build
# Then drag the /build folder to netlify.com/drop
```

### Vercel
```bash
npm install -g vercel
vercel
```

### GitHub Pages
```bash
# Add to package.json: "homepage": "https://yourusername.github.io/webond"
npm install --save-dev gh-pages
npm run build
npx gh-pages -d build
```

---

## ✨ Features
- ✅ Login / Sign Up (Email + Google, Apple, Facebook)
- ✅ Home Feed — Posts, Stories, Compose
- ✅ Like, Comment, Repost, Save, Share
- ✅ Explore — Live search, trending hashtags
- ✅ Reels — TikTok-style vertical feed
- ✅ Full Messaging — Live chat with auto-replies
- ✅ Notifications — Unread badges, mark all read
- ✅ Groups — Join/leave, member counts
- ✅ Events — RSVP going/interested
- ✅ Profile — Edit profile, tabs, media grid
- ✅ Settings — 7 panels, toggles, theme color picker
- ✅ Mobile Responsive — Bottom nav on mobile
- ✅ Keyboard shortcuts (Esc closes modals)

---

**Built by Yusuf Abubakar (Yushat) · Abuja, Nigeria 🇳🇬**
