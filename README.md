# CV Time Tracker

**Camp Village · C.A.U.S.E · Village Printing — Staff Hours**

A professional staff & volunteer time tracking web app. Works on any device, no installation needed.

## Features
- Staff clock in / clock out with 4-digit PIN
- Volunteer list management
- Admin dashboard with all time entries
- CSV export
- Real-time sync across all devices via Firebase
- Admin password protection

## Setup

### 1. Firebase (real-time sync across devices)
1. Go to [console.firebase.google.com](https://console.firebase.google.com)
2. Create a new project → name it `cvtimetracker`
3. Left sidebar → **Build → Realtime Database** → Create Database → Test mode → Enable
4. Left sidebar → ⚙️ **Project Settings** → scroll to **Your apps** → click `</>` → register app
5. Copy the `firebaseConfig` values into `CVTimeTracker.html` where it says `PASTE_YOUR_API_KEY` etc.

### 2. Deploy via GitHub Pages
1. Upload all files to your GitHub repo
2. Go to **Settings → Pages**
3. Source: `main` branch, `/ (root)` → Save
4. Live at: `https://yourusername.github.io/repo-name`

## Default Login
- **Admin password:** `Edwards0011#`
- Change it anytime under Admin → Settings

## First Time Setup
After deploying, log in as Admin and add your staff members and volunteers under the Staff and Volunteers tabs.
