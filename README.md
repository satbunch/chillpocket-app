# 🧊 ChillPocket

**ChillPocket** is a mobile app that lets you carry your fridge in your pocket.  
Snap a photo of your grocery receipt, and the app will automatically extract and organize your items into "Refrigerator" and "Freezer" categories.

Built with **Expo + React Native + TypeScript**.

---

## ✨ Features (Planned)

- 📷 Scan grocery receipts using camera
- 🧠 OCR processing with external API (e.g., CLOVA OCR / Google Vision)
- 🗂️ Auto-classify items into fridge/freezer
- 📦 Manage your current food inventory (quantity, type, expiration date)
- 🔔 Optional notifications for items nearing expiration
- 📱 Designed for fast mobile usage (one-handed UX)

---

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/chillpocket-app.git
cd chillpocket-app
npm install
npx expo start
````

You'll need the **Expo Go app** installed on your smartphone.

---

## 🧩 Tech Stack

* **Expo** (React Native framework)
* **TypeScript**
* **OCR API** (planned: CLOVA or Google Cloud Vision)
* **Supabase or Prisma/PostgreSQL** for backend
* **Tailwind-like styles** via `NativeWind` or `StyleSheet`

---

## 📁 Project Structure

```
chillpocket/
├── assets/         # Icons, splash images, etc.
├── components/     # Reusable UI components
├── screens/        # Camera, OCR Result, Inventory, etc.
├── services/       # API and OCR integrations
├── App.tsx         # Entry point
```

---

## 🛠️ Scripts

```bash
npm run start     # Start Expo development server
npm run lint      # Lint your code
npm run build     # (Planned) Build production version
```

---

## 📌 License

MIT License © 2025

---

## 👾 Author

Built with 🧊 by \[https://github.com/satbunch]
