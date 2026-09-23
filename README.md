# Yuvraj Choudhary — Portfolio Website

Personal portfolio website for Yuvraj Choudhary (BCA AI & ML Student / Aspiring Data Scientist).

## 🚀 Quick Start (Local Development)

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start Local Development Server**:
   ```bash
   npm run dev
   ```
   Open your browser at `http://localhost:5173`.

3. **Build for Production**:
   ```bash
   npm run build
   ```
   The production-ready static assets will be output to the `dist/` directory.

---

## 📦 Project Structure

```
.
├── index.html                  # Main portfolio HTML with Alpine.js & Tailwind CSS
├── public/
│   ├── assets/
│   │   └── profile.jpg        # High-resolution profile photo
│   └── Yuvraj_Choudhary_Resume.pdf  # Downloadable resume PDF
├── package.json               # Project dependencies and npm scripts
├── vercel.json                # Vercel zero-config deployment configuration
├── netlify.toml               # Netlify build & publish configuration
└── README.md                  # Project instructions
```

---

## 🌐 How to Deploy

### Option 1: Deploy to Vercel (Recommended)
1. Push this project to GitHub/GitLab.
2. Go to [Vercel](https://vercel.com/) and click **New Project**.
3. Import your repository. Vercel will automatically detect Vite settings (`npm run build` & `dist` output).
4. Click **Deploy**.

### Option 2: Deploy to Netlify
1. Push this project to GitHub/GitLab.
2. Log in to [Netlify](https://www.netlify.com/) and click **Add new site** > **Import an existing project**.
3. Select your repository. Netlify reads `netlify.toml` automatically.
4. Click **Deploy site**.

### Option 3: GitHub Pages
1. Install `gh-pages` or use GitHub Actions for static deployment.
2. In repository Settings > Pages, set source to GitHub Actions or your build branch (`dist`).
