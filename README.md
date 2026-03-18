# PhoneLab BD

Honest phone reviews for the Bangladesh market.

## First Time GitHub Setup (do this once)

1. Create a new repo on github.com — name it `phonelab-bd`
2. Upload these files to the repo root:
   - `index.html`
   - `phones.json`
   - `README.md`
3. Create a `phones/` folder — upload any phone HTML files inside it
4. Go to repo → **Settings** → **Pages** → Source: **Deploy from branch** → `main` → `/ (root)` → **Save**
5. Wait 1–2 minutes → your site is live at:
   `https://yourusername.github.io/phonelab-bd`

## First Time Site Setup (do this once on the site)

1. Open your site in a browser
2. A setup screen will appear automatically
3. Get a GitHub token:
   - github.com → Settings → Developer Settings → Personal Access Tokens → Tokens (classic)
   - Generate new token → tick `repo` → copy it
4. Fill in the setup form:
   - Paste your token
   - Enter your GitHub username
   - Enter your repo name (`phonelab-bd`)
   - Set a password (you'll use this to unlock the admin panel)
5. Done — token and password are saved in your browser only

## Adding a Phone

1. Get the HTML review file from Claude
2. Click **Add Phone** on the site
3. Enter your password
4. Fill the form — name, price, summary, verdict, tags
5. Upload the HTML file
6. Click **Upload to GitHub**
7. Done — phone appears on the site instantly

## Settings

- **⚙ button** → top right corner
- Change GitHub token anytime
- Change admin password: enter old → new → confirm

## Structure

```
/
├── index.html      ← main site (never edit manually)
├── phones.json     ← auto-managed by the site
├── README.md
└── phones/
    ├── redmi-note-13-pro-5g.html
    ├── oneplus-nord-4.html
    └── ...
```
