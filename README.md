# 📚 PLV BSA Study Hub

An all-in-one, standalone interactive study companion built for **Bachelor of Science in Accountancy (BSA)** students of **Pamantasan ng Lungsod ng Valenzuela (PLV)** and aspiring Filipino CPAs preparing for the **CPALE**.

---

## 🌟 Overview

**PLV BSA Study Hub** (`pinoy-bsa-hub-standalone.html`) is a zero-dependency, self-contained single-page web application designed to streamline accounting review, active recall, and study management. Because everything—styles, scripts, and study modules—is bundled into a single HTML file, it runs seamlessly both online via GitHub Pages and completely offline on any laptop, tablet, or smartphone.

---

## ✨ Key Features

- **Philippine BSA & CPALE Subject Alignment:** Organized around the six core licensure board subjects:
  - **FAR** – Financial Accounting and Reporting (PFRS / PAS)
  - **AFAR** – Advanced Financial Accounting and Reporting
  - **MS** – Management Services
  - **AUD** – Auditing (Theory & Practice)
  - **TAX** – Taxation (Philippine Tax Code, TRAIN & CREATE updates)
  - **RFBT** – Regulatory Framework for Business Transactions
- **Active Recall & Practice Tools:** Interactive reviewers, drills, and concept summaries tailored for retention and problem-solving speed.
- **Study Productivity Suite:** Built-in study organization and focus tools to help manage heavy accounting coursework and departmental exam prep.
- **100% Standalone & Offline-Ready:** No backend server, database setup, or npm build step required—just open the file in any modern web browser.

---

## 🚀 Getting Started

### Option 1: Access Online (GitHub Pages)
Once deployed, open the live site directly in your browser:
```text
https://<your-username>.github.io/<your-repo-name>/
```

### Option 2: Run Offline Locally
1. Download `pinoy-bsa-hub-standalone.html` from this repository (or click **Code → Download ZIP**).
2. Double-click `pinoy-bsa-hub-standalone.html` to open it in Chrome, Edge, Safari, or Firefox.
3. Bookmark the page for instant offline access anytime—even without an internet connection.

---

## 📁 Repository Structure

```text
├── .github/
│   └── workflows/
│       └── deploy.yml                # Automated GitHub Pages deployment workflow
├── pinoy-bsa-hub-standalone.html     # Self-contained single-file web application
└── README.md                         # Project documentation
```

---

## ⚙️ Automated Deployment

This repository uses **GitHub Actions** (`.github/workflows/deploy.yml`) to automatically publish updates to GitHub Pages:
1. Every push to the `main` (or `master`) branch triggers the deployment workflow.
2. The workflow copies `pinoy-bsa-hub-standalone.html` to `_site/index.html` so it loads immediately at the root URL.
3. GitHub Pages deploys the updated static bundle automatically within ~30 seconds.

---

## 📌 Academic Disclaimer

This project is an independent study aid created to support BSA students and reviewees. While structured around Philippine accounting standards and tax laws, always verify critical rules against the latest **BOA CPALE Syllabi**, **PFRS/PAS issuances**, and current **BIR** regulations.