# InfoSphere – Profile Extractor

A web application that extracts and displays user profile information from public websites such as GitHub, blogs, and team pages.  
⚠️ Blocked domains (like LinkedIn) are intentionally excluded.

---

## Features
- Input one or more URLs and extract public profile details (name, bio, image, social links).
- Displays profiles in a **modern card layout**.
- Export results as JSON.
- Copy individual profile JSON directly.
- Works with GitHub, blogs, or public team pages.

---

## Tech Stack
- **Backend:** Python, Flask, BeautifulSoup4, Requests
- **Frontend:** HTML, TailwindCSS, Vanilla JS
- **Other:** CORS enabled for frontend-backend communication

---

## Installation & Setup

### 1. Clone Repo
```bash
git clone https://github.com/Samyuktha-Pari/infosphere-profile-extractor
cd infosphere-profile-extractor
