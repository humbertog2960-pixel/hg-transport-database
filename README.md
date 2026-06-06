# HG-TRANSPORT DATABASE

A single-page, Excel-like customer database app for auto transport businesses. Manage customer records with add/edit/delete, search, sort, print, PDF export, and CSV export — all in your browser.

> **Live demo:** [Open the app](https://humbertog2960-pixel.github.io/hg-transport-database/) (after enabling GitHub Pages)

---

## Features

### 📋 Customer Management
- **Add / Edit / Delete** customer records via modal forms
- **Inline editing** — click any field to edit directly
- **Fields:** Full Name, Phone, Email, Contact Info, Pickup Address, Delivery Address
- **Search** across all fields with real-time filtering
- **Sortable columns** — click Name or Phone headers to sort

### 📊 Dashboard
- **Total Customers, With Email, Total Records** — live stat cards that update on every change
- Stats reflect the currently filtered/search results

### 🖨️ Reporting
- **Print Report** — landscape-optimized layout with summary stats
- **PDF Export** — professional multi-page PDF via jsPDF with pagination and headers
- **CSV Export** — download as CSV with BOM for Excel compatibility

### 🔒 Security
- **Admin account system** — create an account on first use, sign in on return visits
- Once an admin account exists, no additional accounts can be created
- **Session persistence** — stays logged in until you sign out
- **Dark mode toggle** — moon/sun button in the header

### ⚙️ Admin Profile
- **Custom logo upload** — replace the default icon with your company logo (PNG, JPG, GIF, WebP, SVG)
- **Change password** — update your admin password at any time

### 📱 Cross-Platform
- Works on **Windows, Android, and iOS** — any device with a browser
- **Responsive layout** — optimized for phones, tablets, and desktops
- **Touch-friendly** — large touch targets, no sticky hover states on mobile
- **Notch-safe** — respects `env(safe-area-inset-*)` on modern devices

### 💾 Data Storage
- All data is saved automatically in your browser's **localStorage**
- No server, no database, no internet required after the page loads
- Data persists across browser sessions

---

## Getting Started

1. **Open the app** — double-click `hg-transport-database.html` in any modern browser
2. **Create an admin account** — on first launch, set up a username and password
3. **Sign in** — enter your credentials to access the database
4. **Add customers** — click "Add Customer" to start building your database

---

## File Structure

```
├── hg-transport-database.html       # The complete app (single file)
└── README.md                        # This file
```

Everything is contained in a single HTML file — no build tools, no dependencies, no server setup.

---

## Hosting on GitHub Pages

To make the app accessible from any device:

1. Push the file to a GitHub repository
2. Go to **Settings → Pages** in your repo
3. Set the source to **main branch**
4. Your app will be live at `https://humbertog2960-pixel.github.io/hg-transport-database/`

---

## Tech Stack

- **HTML / CSS / JavaScript** — vanilla, no frameworks
- **jsPDF** — PDF generation (loaded from CDN)
- **Inter font** — from Google Fonts
- **localStorage** — client-side data persistence

---

## License

MIT — free to use, modify, and distribute.
