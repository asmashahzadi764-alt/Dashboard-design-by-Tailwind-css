# Tailwind Dashboard

A clean, responsive mentorship dashboard UI built with **HTML** and **Tailwind CSS** (CDN).

---

## 📁 File Structure

```
project/
└── index.html       # Main dashboard file
```

---

## 🚀 How to Run

No build tools or installation needed. Just open the file in any browser:

```
index.html → Right-click → Open with Browser
```

Or use a Live Server extension in VS Code.

---

## 📋 Features

### Stats Section (Section 1)
Three stat cards displayed in a horizontal row:

| Card | Description | Color |
|------|-------------|-------|
| 👥 Active Matches | Shows current active mentorship matches | Purple |
| ✔ Completed Mentorships | Total completed sessions | Green |
| 📅 Pending Requests | Awaiting acceptance requests | Teal |

### Feature Cards (Section 2)
Five action/navigation cards in a wrapping grid:

| Card | Description |
|------|-------------|
| 🔍 Browse Mentors | Find and connect with mentors |
| 🤝 My Matches | View active mentorship relationships |
| 🎯 Goals & Progress | Track SMART objectives |
| ⚙ Settings | Update profile and preferences |
| ⭐ Community Mentors | Explore the mentor community |

---

## 🛠️ Tech Stack

- **HTML5**
- **Tailwind CSS** via CDN (`https://cdn.tailwindcss.com`)

---

## 📐 Layout Details

- Dashboard width: `1000px`, centered with `mx-auto`
- Stat cards: `flex` row with `gap-5`, equal width using `flex-1`
- Feature cards: `300px` wide, wrap layout with `flex-wrap`
- Rounded corners: `rounded-2xl` throughout
- Background: `bg-gray-100` (page), `bg-gray-200` (cards), `bg-white` (stat section)

---

## 🔧 Customization

- Replace `0` values in stat cards with dynamic data from your backend
- Add `href` or `onclick` to feature cards for navigation
- Swap Tailwind CDN with a proper Tailwind build for production use

---

## 📌 Notes

- This is a **static UI prototype** — no JavaScript logic or backend connected
- Tailwind CDN is used for quick development; not recommended for production
- Fixed `1000px` width — consider adding responsive breakpoints for mobile support
