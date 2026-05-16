# 🛠️ Setup Instructions for `aftabhussainofficals` GitHub Profile README

---

## 📦 Repos / Services Used

| Service | Purpose |
|---|---|
| [Capsule Render](https://github.com/kyechan99/capsule-render) | Animated wave header & footer |
| [Visitor Badge](https://github.com/hehuapei/visitor-badge) | Profile view counter |
| [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg) | Animated typing text |
| [Shields.io](https://shields.io) | Social & info badges |
| [Skill Icons](https://github.com/tandpfun/skill-icons) | Tech stack icons |
| [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) | Stats, top langs & pinned repos |
| [Streak Stats](https://github.com/DenverCoder1/github-readme-streak-stats) | Commit streak card |
| [Activity Graph](https://github.com/Ashutosh00710/github-readme-activity-graph) | Contribution activity graph |
| [GitHub Trophies](https://github.com/ryo-ma/github-profile-trophy) | Achievement trophies |
| [Contributions Snake](https://github.com/Platane/snk) | Snake eating your contributions |

---

## 🚀 Quick Setup (Step by Step)

### Step 1 — Create your profile repo
- Create a **new repository** named exactly: `aftabhussainofficals`
- Make it **Public**
- Initialize with a `README.md`

### Step 2 — Enable workflow permissions (REQUIRED for snake to work)
1. Go to your repo → **Settings** tab
2. Left sidebar → **Actions** → **General**
3. Scroll to **Workflow permissions**
4. Select ✅ **Read and write permissions**
5. Click **Save**

> ⚠️ Without this, the snake GitHub Action will fail silently.

### Step 3 — Add the workflow file
- In your repo, create the folder path: `.github/workflows/`
- Upload `main.yml` into that folder (the path must be exactly `.github/workflows/main.yml`)

### Step 4 — Manually trigger the snake for the first time
1. Go to your repo → **Actions** tab
2. Click **Generate Snake** in the left sidebar
3. Click **Run workflow** → **Run workflow** (green button)
4. Wait ~60 seconds for it to complete ✅
5. A new branch called `output` will be created with your snake SVGs

> After this, the snake auto-regenerates every 12 hours and on every push.

### Step 5 — Upload README.md
- Replace your repo's `README.md` with the provided file
- All URLs already use your username `aftabhussainofficals` — no changes needed

---

## 🔧 Customization Guide

### Typing SVG Text
Find the `readme-typing-svg.demolab.com` URLs and edit the `lines=` parameter.
Each line is URL-encoded. Use [this encoder](https://www.urlencoder.org/) to encode your text, then separate lines with `;`.

```
lines=Line+One;Line+Two;Line+Three
```

### Skills / Tech Icons
Find `skillicons.dev/icons?i=` and edit the comma-separated list.
Available icons: https://skillicons.dev

```
https://skillicons.dev/icons?i=python,cpp,c,pytorch,vscode,git&theme=dark
```

### Capsule Render (Header/Footer)
Edit colors at `customColorList=6,11,20` — try values 1–30.
Or change `color=gradient` to a hex like `color=0d1117`.
Full docs: https://github.com/kyechan99/capsule-render

### GitHub Stats Theme
Change `theme=tokyonight` to any other theme:
`dark`, `radical`, `merko`, `gruvbox`, `ocean_dark`, `github_dark`, `dracula`, `nord`, etc.

### Activity Graph Theme
Change `theme=react-dark` at the activity graph URL.
Other options: `github-dark`, `dracula`, `nord`, `tokyo-night`, `xcode`

---

## 🐍 Snake — Troubleshooting

| Problem | Fix |
|---|---|
| Snake image shows as broken link | Run the workflow manually (Step 4 above) |
| Workflow fails with permission error | Enable Read & Write permissions (Step 2) |
| `output` branch doesn't exist | Workflow hasn't run yet — trigger it manually |
| Snake shows old contributions | It regenerates every 12h automatically |
| Dark snake not showing | GitHub auto-picks light/dark via `<picture>` tag |

The snake SVG paths are:
```
Light: https://raw.githubusercontent.com/aftabhussainofficals/aftabhussainofficals/output/github-contribution-grid-snake.svg
Dark:  https://raw.githubusercontent.com/aftabhussainofficals/aftabhussainofficals/output/github-contribution-grid-snake-dark.svg
```

---

## ✅ Checklist Before Going Live

- [ ] Repo named exactly `aftabhussainofficals`
- [ ] Repo is **Public**
- [ ] Read & Write permissions enabled in Actions settings
- [ ] `main.yml` placed at `.github/workflows/main.yml`
- [ ] Workflow triggered manually at least once
- [ ] `output` branch created (visible in branches list)
- [ ] `README.md` uploaded and previewed

---

> ⭐ All services used are **free** and require no API keys or extra accounts.
> The snake, stats, and streak cards all work automatically with your GitHub username.
