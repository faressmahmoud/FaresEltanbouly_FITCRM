# FitCRM — Frontend‑only CRM (HTML + CSS)

**Course:** CSCE 4502 – Design of Web‑Based Systems (Fall 2025)  
**Project Type:** Frontend‑only (HTML and CSS only)  
**Target Users:** Fitness instructors, personal trainers, small gyms  
**Purpose:** Manage basic client information and track fitness goals.

---

## Folder Structure
```
fitcrm/
├── index.html          # New Client Form
├── clients.html        # Client List (10 sample clients)
├── css/
│   └── styles.css
├── assets/
│   └── icons/          # placeholder directory
└── README.md
```

---

## Functional Requirements Coverage

| Requirement | Status |
|--------------|---------|
| Full Name (text) | ✔️ |
| Age (number input) | ✔️ `<input type="number" min='0' max='120'>` |
| Gender (dropdown) | ✔️ Female / Male / Prefer not to say |
| Email (email input) | ✔️ |
| Phone (tel input) | ✔️ |
| Fitness Goal (datalist) | ✔️ Weight Loss, Muscle Gain, General Fitness, Endurance, Flexibility |
| Membership Start Date (date input) | ✔️ |
| Add Client button (visual only) | ✔️ Placeholder only |
| Client List (10 rows) | ✔️ |
| Responsive layout | ✔️ CSS Grid/Flex + scrollable table |

---

## Run Locally
Open `index.html` or `clients.html` directly in any modern browser.

---

## Deploy to GitHub Pages
1. Create a **public repository** (e.g., `fitcrm`).  
2. Upload the entire folder or push via Git:
   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "FitCRM: initial release"
   git remote add origin https://github.com/<USERNAME>/fitcrm.git
   git push -u origin main
   ```
3. In GitHub: **Settings → Pages → Source:**  
   - Branch: `main`  
   - Folder: `/ (root)`  
4. Wait 1–2 minutes for the site to publish.

## Deployment Links

- **GitHub Repo:** https://github.com/faressmahmoud/FaresEltanbouly_FITCRM  
- **Live App (GitHub Pages):** https://faressmahmoud.github.io/FaresEltanbouly_FITCRM/  
  - New Client: https://faressmahmoud.github.io/FaresEltanbouly_FITCRM/index.html  
  - Client List: https://faressmahmoud.github.io/FaresEltanbouly_FITCRM/clients.html

---


© 2025 FitCRM — coursework demo.
