# SUKOON — Public Legal, Compliance & GitHub Pages Website

This folder contains the complete, self-contained public website and legal documentation for the **SUKOON** Android application (`com.syedahmed.sukoon`).

Everything in this folder is **production-ready** and designed to be uploaded directly to a public GitHub repository named `sukoon` to host via **GitHub Pages**.

---

## 📁 Folder Structure

```
github/
│
├── index.html                  # Main Public Landing & Legal Hub
├── README.md                   # This instruction guide
│
├── privacy-policy/
│   └── index.html              # Official Google Play Privacy Policy
│
├── terms/
│   └── index.html              # Terms of Use (Devotional & Non-Commercial)
│
├── support/
│   └── index.html              # Support, FAQ & Troubleshooting
│
├── attribution/
│   └── index.html              # Sources & Licensing (Tanzil, Saheeh Int., Amiri)
│
└── about/
    └── index.html              # Product Philosophy & Developer Attribution
```

---

## 🚀 How to Publish on GitHub Pages (Step-by-Step)

### Step 1: Create a Public GitHub Repository
1. Log in to [GitHub](https://github.com).
2. Click the **`+`** icon in the top right and select **New repository**.
3. Set the Repository name to: `sukoon`
4. Choose **Public** (required for free GitHub Pages).
5. Leave "Add a README file" unchecked (this folder already provides one).
6. Click **Create repository**.

### Step 2: Upload Files (Drag and Drop)
1. On your computer, open this `github` folder (`Y:\CLINT WORK FOR A2\SOFTWARE\QURAN APP\github`).
2. Select **all files and folders** inside:
   - `index.html`
   - `privacy-policy/`
   - `terms/`
   - `support/`
   - `attribution/`
   - `about/`
   - `README.md`
3. Drag and drop them directly onto the GitHub repository web page, or use the **"uploading an existing file"** link.
4. Type a commit message (e.g. `Initial commit of SUKOON legal and compliance site`).
5. Click **Commit changes**.

### Step 3: Enable GitHub Pages
1. In your GitHub repository, click on the **Settings** tab.
2. In the left sidebar, click **Pages** (under "Code and automation").
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` (or `master`) and folder `/(root)`.
4. Click **Save**.
5. Wait 1–2 minutes. GitHub will display a notification saying your site is live!

---

## 🌐 Your Live URLs

Once published, your pages will be accessible at:

| Page | Live Public URL |
|---|---|
| **Main Legal Hub** | `https://<username>.github.io/sukoon/` |
| **Privacy Policy (Google Play)** | `https://<username>.github.io/sukoon/privacy-policy/` |
| **Terms of Use** | `https://<username>.github.io/sukoon/terms/` |
| **Support & FAQ** | `https://<username>.github.io/sukoon/support/` |
| **Attribution & Sources** | `https://<username>.github.io/sukoon/attribution/` |
| **About SUKOON** | `https://<username>.github.io/sukoon/about/` |

> Replace `<username>` with your actual GitHub username.

---

## 📋 Google Play Console Submission Link

When Google Play Console asks for your **Privacy policy URL**:
```text
https://<username>.github.io/sukoon/privacy-policy/
```

---

## 🔒 Design & Compliance Guarantees

- **100% Self-Contained:** Zero external CSS, fonts, or scripts. Fully responsive on mobile and desktop.
- **Zero Tracking:** No cookies, analytics, trackers, or third-party web beacons.
- **JavaScript-Free:** All pages function perfectly with JavaScript disabled.
- **Relative Linking:** Internal navigation uses relative links (`../privacy-policy/`, `../`, etc.), so the site works on any domain or subdomain without modification.
- **Zero Secrets:** No passwords, keystores, or API tokens are contained in this folder.
