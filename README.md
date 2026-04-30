# 🍽️ Trinity Restaurant — Official Website

> *"Taste the Trinity of Flavors"*  
> A premium dining experience at Hesaraghatta, Bengaluru — Est. 2024

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-gold?style=for-the-badge)](https://YOUR-USERNAME.github.io/trinity-restaurant)
[![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-181717?style=for-the-badge&logo=github)](https://pages.github.com/)

---

## 📸 Preview

![Trinity Restaurant Homepage](assets/preview.png)

---

## 🌟 Features

- 🏠 **Home** — Hero slideshow, featured dishes, dining hall previews
- 📖 **About** — Founders section, mission & vision
- 🍛 **Menu** — Categorized menu with 120+ items, filterable by cuisine
- 🏛️ **Dining Halls** — 4 unique spaces: Skyrane Hall, Desire Courtyard, Snack Arena, Sky Lounge
- 🛒 **Online Order** — Add to cart, cart sidebar, checkout flow
- 📅 **Reservations** — Full reservation form with hall selection
- 📞 **Contact** — Map embed, contact form, business hours

---

## 🗂️ Project Structure

```
trinity-restaurant/
│
├── index.html          ← Main HTML file (entire site)
├── css/
│   └── style.css       ← All styles (dark luxury theme)
├── js/
│   └── main.js         ← Navigation, cart, menu logic
├── assets/
│   └── preview.png     ← Screenshot for README (add manually)
│
├── README.md           ← You are here
├── .gitignore          ← Files to exclude from git
└── LICENSE             ← MIT License
```

> ✅ **Pure Frontend** — No backend, no database, no server needed.  
> Everything runs in the browser. Perfect for GitHub Pages hosting.

---

## 🚀 How to View Locally

### Option 1 — Just open the file
```bash
# 1. Clone the repo
git clone https://github.com/YOUR-USERNAME/trinity-restaurant.git

# 2. Navigate into it
cd trinity-restaurant

# 3. Open index.html in your browser
# On Windows:
start index.html

# On Mac:
open index.html

# On Linux:
xdg-open index.html
```

### Option 2 — Use VS Code Live Server (Recommended)
```bash
# 1. Clone the repo
git clone https://github.com/YOUR-USERNAME/trinity-restaurant.git

# 2. Open in VS Code
cd trinity-restaurant
code .

# 3. Install "Live Server" extension in VS Code
# 4. Right-click index.html → "Open with Live Server"
# 5. Browser opens at http://localhost:5500
```

### Option 3 — Python simple server
```bash
cd trinity-restaurant

# Python 3
python -m http.server 8000

# Then open: http://localhost:8000
```

---

## 🌐 Deploy to GitHub Pages (Free Hosting)

Anyone with your GitHub link can view the live site. Here's how to set it up:

### Step 1 — Create the Repository
1. Go to [github.com](https://github.com) → Sign in
2. Click **"New repository"** (green button)
3. Name it: `trinity-restaurant`
4. Set to **Public**
5. ✅ Check **"Add a README file"** — then we'll replace it
6. Click **"Create repository"**

### Step 2 — Upload Your Files
```bash
# On your computer, open terminal/command prompt
cd path/to/your/trinity-restaurant/folder

# Initialize git
git init

# Add all files
git add .

# First commit
git commit -m "🍽️ Initial commit — Trinity Restaurant website"

# Link to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/trinity-restaurant.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** tab
3. Scroll to **"Pages"** in the left sidebar
4. Under **"Source"** → Select **"Deploy from a branch"**
5. Branch: **main** | Folder: **/ (root)**
6. Click **Save**
7. Wait 2–3 minutes ⏳
8. Your site is live at:  
   **`https://YOUR-USERNAME.github.io/trinity-restaurant`**

---

## ✏️ Making Changes & Updating the Live Site

```bash
# After editing any file locally:

git add .
git commit -m "✨ Update menu items"
git push

# GitHub Pages auto-updates within 1–2 minutes!
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure & content |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | Navigation, cart, menu filtering |
| Google Fonts | Cormorant Garamond, Josefin Sans, Playfair Display |
| Unsplash | Stock photography (free to use) |
| GitHub Pages | Free static site hosting |

**No frameworks. No build tools. No npm install.**  
Open `index.html` and it just works. ✅

---

## 📱 Responsive Design

The website is fully responsive:
- 🖥️ Desktop (1440px+)
- 💻 Laptop (1024px)
- 📱 Tablet (768px)
- 📲 Mobile (375px)

---

## 👨‍💼 Founders

| Name | Role |
|---|---|
| **Arun Kumar N A** | Lead & Vision · Chief Architect |
| **Akashh M S** | Co-Founder · Operations Head |
| **Prakash Desai** | Co-Founder · Culinary Director |

---

## 📬 Contact

- 📞 +91 93456 78210 · +91 81234 99876
- ✉️ contact@trinityrestaurant.in
- 📍 Hesaraghatta, Bengaluru – 560090, Karnataka, India

---

## 📄 License

MIT License — feel free to use this as a template.  
© 2024 Trinity Restaurant. Founded by Arun Kumar N A, Akashh M S & Prakash Desai.
