# Lakshmi Prasanna Saladi — Developer Portfolio

A responsive, accessible, static personal portfolio website designed for entry-level software engineering opportunities. Built with pure **HTML5, Vanilla CSS, and Vanilla JavaScript** with zero build tools or external dependencies.

---

## 🌟 Key Engineering & Design Highlights

- **Pure Web Standards:** Clean separation of concerns across `index.html`, `style.css`, and `script.js` without framework bloat.
- **Fast Performance:** Static asset architecture with near-instant Time to First Byte (TTFB) and high Core Web Vitals scores.
- **Responsive Design:** Mobile-first fluid layout engineered with CSS Grid, Flexbox, and `clamp()` typography, tested across mobile, tablet, and desktop viewports.
- **Accessibility (WCAG 2.1 AA Compliant):**
  - Skip-to-content bypass link with programmatic focus management.
  - Semantic HTML5 landmark structure (`header`, `nav`, `main`, `section`, `article`, `footer`).
  - Mobile navigation with full keyboard support (<kbd>Escape</kbd> key handling, outside click dismissal, focus trap management, and aria states).
  - Respects `@media (prefers-reduced-motion)` for users sensitive to motion.
  - High contrast color palette tailored for readability.
- **Recruiter-Focused Structure:** Direct access to current role at People Prime Worldwide, AI web platforms development, academic projects, technical skills, verified education, and a direct PDF resume download.

---

## 📂 Project Structure

```text
lakshmi-portfolio/
├── assets/
│   └── Lakshmi-Prasanna-Saladi-Resume.pdf   # Verified downloadable resume
├── index.html                               # Semantic structure, Open Graph metadata, inline SVG favicon
├── style.css                                # Design system tokens, typography, responsive breakpoints
├── script.js                                # Accessible mobile navigation logic
└── README.md                                # Project documentation & deployment guide
```

---

## 🚀 Running Locally

### Option 1: Direct File Opening
Double-click `index.html` in your file explorer to open it directly in any modern browser.

### Option 2: Python Local Server (Recommended)
If you have Python installed, run:
```bash
python -m http.server 8000
```
Then open [http://localhost:8000](http://localhost:8000) in your web browser.

### Option 3: VS Code Live Server
1. Open this folder in **VS Code**.
2. Install the **Live Server** extension (by Ritwick Dey).
3. Right-click `index.html` and choose **Open with Live Server**.

---

## 🌐 Deploying to GitHub Pages (Step-by-Step)

Follow these steps to deploy your portfolio live on GitHub Pages for free:

### Step 1: Initialize Git and Commit
In your terminal (inside the `lakshmi-portfolio` folder):
```bash
git init
git add .
git commit -m "Initial commit of Lakshmi Prasanna portfolio"
```

### Step 2: Push to GitHub
1. Go to [GitHub.com](https://github.com) and create a new public repository named `portfolio` (or `lakshmi-prasanna-portfolio`).
2. Link your local project to the GitHub repository:
```bash
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. On GitHub, navigate to your repository's **Settings** tab.
2. In the left sidebar, click on **Pages** (under the "Code and automation" section).
3. Under **Build and deployment** > **Source**, select **Deploy from a branch**.
4. Under **Branch**, select `main` and keep the folder set to `/ (root)`.
5. Click **Save**.
6. After 1–2 minutes, your website will be live at:
   `https://<your-username>.github.io/<your-repo-name>/`

---

## 💼 Interview Talking Points & Technical Explanations

When recruiters and interviewers ask about your portfolio, you can highlight:

1. **Why Vanilla HTML/CSS/JS instead of React or Tailwind?**
   > *"I intentionally chose a zero-framework stack to demonstrate my mastery of core web fundamentals. Frameworks add build complexity and bundle overhead that aren't necessary for a static portfolio. By using standard HTML5, CSS custom properties, and modern DOM APIs, the site loads instantly, is easy to maintain, and achieves maximum portability."*

2. **How did you approach accessibility?**
   > *"I adhered to WCAG 2.1 standards: implementing a skip-link for keyboard users, ensuring semantic heading hierarchy (a single `<h1>` followed by logical `<h2>` and `<h3>` tags), adding `aria-expanded` and `aria-label` indicators for screen readers, and building a keyboard-friendly mobile navigation menu that responds to the Escape key and outside clicks."*

3. **How is the responsive layout engineered?**
   > *"Rather than relying on heavy utility libraries, I built a lightweight CSS design system using CSS Grid for multi-column cards, Flexbox for interface alignment, and fluid `clamp()` sizing for typography so text scales naturally between small phone viewports and large desktop monitors."*

---

## 🔒 Content Accuracy & Privacy Notice
- All projects, technologies, and educational credentials reflect verified background information. Current role reflects active employment at People Prime Worldwide.
- **Privacy check:** Please verify whether you want your direct phone number publicly indexed on the web before deploying. You can easily remove the phone number and rely on the LinkedIn and Email contact buttons if preferred.
