# ⚡ Sohel Khan — Shinobi Portfolio

> **"Believe it. Work for it. Achieve it."**  
> A modern, visually impressive personal portfolio website for **Sohel Khan**, B.Tech Computer Science Engineering (CSE Core) student at **JECRC University**. Built with a Naruto-inspired ninja aesthetic, dark chakra glow effects, dynamic canvas flame particles, and a professional software engineer layout.

---

## 🌟 Features & Highlights

- **Ninja Aesthetic with Professional Execution:** Dark black/navy canvas (`#05070e`), Kurama flame & Sage orange accents, Will of Fire crimson, and subtle Japanese geometric patterns (Asanoha/Seigaiha).
- **Interactive Chakra Background:** Real-time HTML5 Canvas particle system generating rising glowing chakra embers with interactive cursor repulsion.
- **Hero Section:** Features your name, degree, university, official tagline, and dual high-impact call-to-actions.
- **Official Shinobi Profile (About Me):** Showcases your background at JECRC University, your passion for technology and sports, and your Nindo (continuous improvement, discipline, teamwork).
- **Academy Timeline (Education):** Dedicated card for JECRC University B.Tech CSE Core.
- **Shinobi Skillset (No Fake Percentages):** Animated cards for C Programming, Python, HTML, CSS, JavaScript, Problem Solving, Communication, and Teamwork.
- **My Ninja Journey:** Creative timeline connecting: `Academics → Skills → Projects → Sports → Future Goals` with glowing chakra energy lines.
- **Featured Missions (Projects):** Cards with tags, live links, and GitHub buttons for Portfolio Website, C Programming Project, and Future Project.
- **Fuel For The Soul (Hobbies & Interests):** Highlighting Sports 🏆, Tech & Coding ⚡, Learning New Skills 🎯, and Personal Growth 🔥.
- **Badges of Honor (Achievements):** Clean, editable placeholders for Academic, Sports, Certifications, and Competitions.
- **Ninja Scroll Dispatch (Contact):** Validated contact form with interactive confirmation modal and social placeholders (GitHub, LinkedIn, Instagram).
- **Dual Architecture:**
  1. **Root Static Site (`index.html`, `css/`, `js/`):** Instantly deployable to GitHub Pages with 0 build steps.
  2. **React + Tailwind Source (`react-version/`):** Modular React 18 + Tailwind Vite project.

---

## 🚀 How to Deploy on GitHub (in 2 Minutes)

You can deploy this site for **free** on GitHub Pages using either of the two easy methods below:

### Method 1: Upload Directly via GitHub Web (No Git Required)

1. Log in to [GitHub](https://github.com/) and click **New Repository**.
2. Name your repository (e.g. `portfolio` or `sohel-portfolio`).
   - *Tip:* If you name it `<your-github-username>.github.io` (e.g. `sohelkhan.github.io`), your site URL will be clean without any subfolders!
3. Set the repository to **Public** and click **Create repository**.
4. On the new repository page, click the link that says **"uploading an existing file"**.
5. Drag and drop all the files and folders from `sohel-khan-portfolio` (ensure `index.html` is at the root level).
6. Click **Commit changes**.
7. Go to **Settings** (tab at the top of your repository) → **Pages** (in the left sidebar).
8. Under **Build and deployment**:
   - **Source:** Choose `Deploy from a branch`
   - **Branch:** Select `main` (or `master`) and folder `/ (root)`
   - Click **Save**.
9. Wait about 30–60 seconds, refresh the page, and GitHub will display your live website link:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

---

### Method 2: Deploy Using Git Command Line

If you have Git installed on your computer:

```bash
# 1. Navigate to the project directory
cd sohel-khan-portfolio

# 2. Initialize git repository
git init

# 3. Add all files and make initial commit
git add .
git commit -m "Initial commit: Sohel Khan Shinobi Portfolio"

# 4. Link your GitHub remote repository (replace with your repo URL)
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git

# 5. Push to GitHub
git push -u origin main
```

Then go to **Repository Settings → Pages → Deploy from branch `main` / `(root)` → Save**.

---

## 💻 How to View Locally on Your Computer

1. Open File Explorer and navigate to:
   `sohel-khan-portfolio/`
2. Simply **double-click `index.html`**.
3. It will open in your default browser (Chrome, Edge, Brave, Firefox) with all animations, canvas chakra particles, and responsive styles working immediately!

---

## 🛠️ How to Customize Your Details

All personal information is cleanly organized in `index.html`:

| To Customize | File & Location in `index.html` |
|---|---|
| **Social Links** | Search for `github.com/sohelkhan`, `linkedin.com/in/sohelkhan`, `instagram.com/sohelkhan` and replace with your real URLs |
| **Email Address** | Search for `sohelkhan@example.com` and replace with your actual email |
| **Project Links** | In `#projects`, update the `href` on the `View Project` buttons |
| **Achievements** | In `#achievements`, replace `[Editable: ...]` text with your awards, sports medals, or certifications |

---

## ⚛️ Developing with React + Tailwind (Optional)

If you wish to run or develop using the modular React Vite codebase:

```bash
cd react-version
npm install
npm run dev
```

To build production static assets:
```bash
npm run build
```

---

## 📜 Shinobi Motto
> **"Sohel Khan — Keep Moving Forward ⚡"**  
> *火の意志 (Will of Fire)*
