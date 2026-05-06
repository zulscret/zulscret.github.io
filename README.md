# Muhammad Zulvan Yahya — Portfolio Website

Personal portfolio website built with pure HTML, CSS, and JavaScript.

🌐 **Live URL:** https://zulscret.github.io

---

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles (dark theme, glassmorphism, responsive)
├── js/
│   └── main.js         # Animations, typing effect, contact form
├── assets/
│   ├── foto-profil.png # Profile photo
│   ├── cv.pdf          # Downloadable CV
│   └── project-*.jpg  # Project screenshots
└── README.md
```

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create GitHub Repo
1. Go to [github.com/new](https://github.com/new)
2. Repository name: **`zulscret.github.io`** (must match your username exactly)
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Push this folder
```bash
cd "c:\Users\ASUS\OneDrive\Dokumen\Portofolio Zulvan New\portfolio-website"
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/zulscret/zulscret.github.io.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/ (root)`
3. Save — your site will be live at **https://zulscret.github.io** in ~2 minutes!

---

## 📧 Setup Formspree (Free Contact Form)

1. Go to [formspree.io](https://formspree.io) and **Sign Up** (free)
2. Click **+ New Form**, enter your email `zpan949@gmail.com`
3. Copy the **Form ID** (e.g. `xyzabcde`)
4. Open `index.html`, find this line:
   ```html
   action="https://formspree.io/f/YOUR_FORM_ID"
   ```
5. Replace `YOUR_FORM_ID` with your actual form ID
6. Done! Free plan: 50 submissions/month

---

## 🎨 Features
- ✅ Dark mode with glassmorphism design
- ✅ Typing animation in hero
- ✅ Scroll reveal animations
- ✅ Mobile responsive
- ✅ Sticky navbar with active states
- ✅ Downloadable CV
- ✅ Working contact form (via Formspree)
- ✅ All sections: Hero, About, Skills, Experience, Projects, Education, Contact
