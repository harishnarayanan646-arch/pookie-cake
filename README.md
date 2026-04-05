# 🎂 Pookie Cakes

A beautiful, fully-featured cake shop web app built with vanilla HTML, CSS & JavaScript.

## 🌟 Features

- 🛒 Shopping cart with quantity controls
- 💬 WhatsApp ordering (Click-to-Chat)
- 📲 WhatsApp Business API — auto order confirmation to customer
- 📍 Google Maps link in every order message
- 🎂 AI Cake Wizard (suggests cakes based on occasion & budget)
- 👤 User login / signup / Google Sign-In
- 📦 Order tracking with live status
- 🔧 Admin dashboard (add cakes, set prices, manage UPI & WhatsApp number)
- 🎁 Offers, coupons & loyalty points
- 📱 Fully mobile responsive

## 🚀 Live Demo

> Hosted on GitHub Pages:
> **https://YOUR-USERNAME.github.io/pookie-cakes/**

## 📁 Project Structure

```
pookie-cakes/
│
├── index.html          ← Main app (entire frontend)
├── README.md           ← This file
├── .gitignore          ← Files to ignore in Git
│
└── assets/
    ├── css/
    │   └── README.md   ← CSS is inside index.html (inline)
    ├── js/
    │   └── README.md   ← JS is inside index.html (inline)
    └── images/
        └── README.md   ← Images loaded from Unsplash URLs
```

## ⚙️ Setup & Usage

### 1. Clone the repo
```bash
git clone https://github.com/YOUR-USERNAME/pookie-cakes.git
cd pookie-cakes
```

### 2. Open locally
Just open `index.html` in any browser — no server needed!

### 3. Configure your settings
Open `index.html` and find these sections to customize:

#### WhatsApp Business API (line ~3394)
```js
const WA_API_CONFIG = {
  phoneNumberId: "YOUR_PHONE_NUMBER_ID",
  accessToken:   "YOUR_ACCESS_TOKEN",
  enabled: true
};
```

#### Baker's WhatsApp number & UPI (Admin Panel)
- Open the app → click **Admin** (top right)
- Login: `pookieadmin` / `cake@2025`
- Update WhatsApp number, UPI ID, shop name

## 📲 WhatsApp Setup

| Step | What to do |
|------|-----------|
| 1 | Go to [developers.facebook.com](https://developers.facebook.com) |
| 2 | Create app → Add WhatsApp product |
| 3 | Get Phone Number ID + Access Token |
| 4 | Paste into `WA_API_CONFIG` in `index.html` |

> ⚠️ Temporary tokens expire in **24 hours**. Generate a permanent System User Token for production.

## 🔑 Admin Credentials

| Field | Value |
|-------|-------|
| Username | `pookieadmin` |
| Password | `cake@2025` |

> ⚠️ Change these before going live!

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (no frameworks)
- **Fonts:** Google Fonts (Caveat + Nunito)
- **Images:** Unsplash CDN
- **Ordering:** WhatsApp Business API (Meta)
- **Auth:** Custom + simulated Google Sign-In
- **Storage:** localStorage (no backend needed)

## 📦 Deployment (GitHub Pages)

1. Push to GitHub
2. Go to repo **Settings → Pages**
3. Set branch to `main`, folder to `/root`
4. Save → live in 2 minutes at `https://YOUR-USERNAME.github.io/pookie-cakes/`

## 💖 Made with love in Chennai, India 🇮🇳

---
*Pookie Cakes v2.0 — Sweet Treats Delivered!* 🎂
