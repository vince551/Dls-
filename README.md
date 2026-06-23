# 🏆 Dream League Soccer (DLS) Tournament Hub

A high-energy, mobile-responsive web dashboard designed for managing local Dream League Soccer tournaments. Built with a sleek console-style UI featuring glassmorphism elements, neon accents, and custom tactical shapes inspired by the real game.

## 🚀 Live Demo
Once your GitHub Pages deployment is active, you can access your live hub here:
`https://your-username.github.io/your-repository-name/`

---

## ⚡ Features

* **DLS Style UI:** Immersive dark theme with electric neon greens, stadium light backdrops, and slanted navigation widgets.
* **Live-Calculating League Table:** Automatically tallies Points (Pts), Played (P), Wins (W), Draws (D), Losses (L), and Goal Difference (GD). Ties are broken dynamically based on goal records.
* **Knockout Bracket Generator:** Instantly seeds registered players into automated Round 1 matchups with smart 'BYE' support for odd player numbers.
* **Admin Authentication Gate:** Secured with an email/password prompt to restrict tournament adjustments, registration, and data resets to the organizer only.
* **Matchmaking Chat Interface:** A streamlined workspace area for users to coordinate room codes or discuss scores.
* **Persistent Storage:** Powered by `localStorage` so your data stays saved on your browser even if you close the tab.

---

## 🛠️ Setup & Files Structure

To make sure your custom images load correctly, your GitHub repository structure should look like this:

├── index.html
└── images/
    ├── logo.png
    └── background.jpg

---

## 🔐 Admin Configuration
The default login credentials for tournament administration are preconfigured within the script:
* **Admin ID:** `architectvince7@gmail.com`
* **Security PIN:** `architectvince@123#$`

---

## 📝 How to Run Your Tournament

1.  **Register Teams:** Navigate to the Admin Panel, authenticate, and register each participant's team/manager name.
2.  **Generate Matches:** Use the **Tournament Control** widget to shuffle and build your knockout pairings.
3.  **Update Scores:** Input match scoreboards directly into the **Report Match Score** calculator to automatically re-rank the league standings in real-time.
