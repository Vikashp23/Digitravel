# 🧭 DigiTravel – India's Smart Travel Knowledge Platform

DigiTravel is a static-first travel planning platform designed to simplify Indian itineraries, highway stopover discoveries, group expense tracking, and non-biased platform comparisons.

## 🚀 Key Features
* **100% GitHub Pages Compatible**: Constructed using pure HTML5, CSS3 (Glassmorphism design), and Vanilla Javascript (ES6).
* **Location & Route Intelligence**: Provides highway checkpoints, driving times, food stops, and Google Maps previews for Indian travel routes.
* **Non-Booking Platform Comparison**: Connects users to official sources (like IRCTC, KSRTC, IndiGo) without selling tickets directly.
* **Group Expense Splitter**: Features an integrated expense manager that exports shareable summaries to WhatsApp and PDF.
* **Floating AI Assistant**: Redirects queries to WhatsApp or Telegram bots via `config.json`.

---

## 🛠️ Deployment Instructions (GitHub Pages)
1. Commit and push the repository to your GitHub account.
2. Navigate to **Settings > Pages** within your GitHub repository.
3. Under **Branch**, select `main` (or `master`) and specify the `/ (root)` directory.
4. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repository-name>/`.

---

## ⚡ Future Firebase Integration
To enable Firebase Authentication and Firestore synchronization:
1. Create a Firebase project at the [Firebase Console](https://console.firebase.google.com/).
2. Obtain your web app configuration credentials.
3. Open `js/firebase-config.js` and update the `firebaseConfig` object keys.

---

## ➕ Adding New States or Destinations
Edit `json/destinations.json`:
* Add new entries to `states` to update the **India Explorer** grid.
* Add complete travel profiles under `featuredDestinations` including `checkpoints`, `foodStops`, and `faqs`.