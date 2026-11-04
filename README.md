# 🏦 Bank Asia Branch Activity & Mystery Shopping Tracker (Interactive Web App)

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmonourhosan%2FBranch_Activity_Tracker_Interactive)
![Status](https://img.shields.io/badge/Status-Production%20Ready-emerald)
![Platform](https://img.shields.io/badge/Platform-Vercel%20%7C%20GitHub-blue)
![Scope](https://img.shields.io/badge/Scope-68%20Branches%20%7C%20698%20Activities-purple)

> **Client / Organization:** Innovative Creation Ltd. (IRC) & Bank Asia  
> **Project Scope:** Mystery Shopping & Branch Compliance Field Activities (68 Branches nationwide across Chittagong, Dhaka North, and East regions)  
> **Target Activities:** 698 Active Slots (29×12 + 19×10 + 20×8)

---

## 🚀 Live Demo on Vercel

You can deploy and run this repository live on Vercel with zero configuration:
1. Click the **[Deploy with Vercel](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fmonourhosan%2FBranch_Activity_Tracker_Interactive)** button above.
2. Or go to [vercel.com](https://vercel.com), click **"Add New Project"**, select `Branch_Activity_Tracker_Interactive`, and click **Deploy**.
3. Vercel automatically deploys `index.html` and gives you an instant live URL (e.g., `https://branch-activity-tracker-interactive.vercel.app`).

---

## ✨ Key Features

- **Individual Branch Activity Management:**
  - **8-Activity Branches (20 branches):** Activities 01–08 active; 09–12 locked as `N/A`.
  - **10-Activity Branches (19 branches):** Activities 01–10 active; 11–12 locked as `N/A`.
  - **12-Activity Branches (29 branches):** All 12 activities fully active.
- **Interactive Checkboxes (☑ Yes / ☐ No):** Click any activity slot to toggle status instantly with soft green / coral status styling.
- **Individual Date & Time Pickers:** Native HTML5 Date (`YYYY-MM-DD`) and Time (`HH:MM`) pickers for every single activity slot.
- **Auto-Timestamp:** Clicking a pending activity automatically pre-populates today's date and current time if blank!
- **Real-Time KPI Dashboard:** Instant progress percentage, completed count, and pending count calculated live at both the branch card and overall project level.
- **Dual View Modes:**
  - **Cards View:** Clean card layout showing branch details, coordinator, and activity grid.
  - **Matrix Table View:** Spreadsheet-style matrix displaying all 36 activity sub-columns.
- **Instant Search & Filter:** Filter by region (*Chittagong*, *Dhaka North*, *East*), activity tier (*8-Act*, *10-Act*, *12-Act*), or search by name, code, district, or coordinator.
- **Data Persistence:** Automatically saves your updates to browser `localStorage` so data is never lost on refresh.
- **One-Click Export:** Export current live progress to clean CSV anytime.
- **Downloadable Master Excel:** Includes direct download link to [`Branch_Activities_Master_Tracking_2026.xlsx`](./data/Branch_Activities_Master_Tracking_2026.xlsx) with 9 automated sheets, formulas, and data validations.

---

## 📂 Repository File Structure

```
Branch_Activity_Tracker_Interactive/
├── index.html                                   # Primary Vercel entrypoint (HTML5 interactive web app)
├── Branch_Activity_Tracker_Interactive.html     # Mirror entrypoint for backward compatibility
├── vercel.json                                  # Vercel deployment routes, rewrites & headers
├── package.json                                 # Project metadata and serve scripts
├── .gitignore                                   # Ignore list for deployment builds
├── README.md                                    # Documentation and Vercel deploy badge
└── data/
    ├── Branch_Activities_Master_Tracking_2026.xlsx  # Official 9-sheet Master Excel Workbook
    └── Branch list_25th Oct'2026.xlsx               # Original source dataset
```

---

## 🛠️ Deploying to Vercel Step-by-Step

### Method 1: Using the Vercel Web Dashboard (Recommended)
1. Sign in to [Vercel](https://vercel.com).
2. Click **Add New...** &rarr; **Project**.
3. Import your GitHub repository: `monourhosan/Branch_Activity_Tracker_Interactive`.
4. Framework Preset: **Other** (Root Directory: `./`).
5. Click **Deploy**. Vercel will complete deployment in ~10 seconds!

### Method 2: Using Vercel CLI
```bash
# Install Vercel CLI (if not already installed)
npm install -g vercel

# Deploy directly from your terminal
vercel --prod
```

---

## 💻 Local Preview
To test locally before deploying:
```bash
# Using python built-in server:
python -m http.server 3000

# Or using npx serve:
npx serve .
```
Then visit `http://localhost:3000` in your web browser.

---

## 📄 License & Credits
- **Client / Organization:** Innovative Creation Ltd. (IRC)
- **Partner Institution:** Bank Asia
- **Author:** Monour Hosan Saif ([@monourhosan](https://github.com/monourhosan))
- **License:** MIT
