# 📊 Angular Crypto Price Chart App

A clean, modern, and responsive cryptocurrency price chart application built using **Angular 19**, **SCSS**, and a **service-driven architecture**.  
Includes real-time chart updates, coin & currency selection, and adjustable time ranges — all wrapped in a **beautiful, consistent UI**.

---

## 🌐 Live Demo

👉 [Click here to try the app](https://ahmad-889.github.io/crypto-charts/)

---

## 🎯 What I Built

This application is designed with **standalone components** for scalability and maintainability.  
Here’s what’s inside:

* ✅ `CryptoOptionsComponent`: A modern, consistent form for selecting coin, currency, and time range  
* ✅ `CryptoChartComponent`: Displays interactive charts with updated data  
* ✅ `CryptoService`: Fetches price history and current data from a public API  
* ✅ Responsive, dark-themed UI with polished SCSS styling

---

## 💡 Key Features

* 💹 **Select any cryptocurrency** and display its historical prices  
* 💱 **Choose currency** for price conversion (USD, EUR, etc.)  
* ⏳ **Adjust time range** for the chart (e.g., last 7, 30, 90 days)  
* 🎨 **Modern, consistent form design** with focus and hover effects  
* 📱 Fully responsive layout for desktop and mobile  
* ⚡ Fast data loading with caching where possible

---

## 🧱 Technologies Used

* Angular 19 (Standalone Components)
* TypeScript
* SCSS (Custom, consistent styling + Responsive Design)
* RxJS + Angular HTTPClient
* Chart.js (or similar) for chart rendering
* Public Cryptocurrency API (e.g., CoinGecko API)

---

## 📸 Screenshot

![Crypto Chart UI](public/screenshot.png)

---

## 📁 Project Structure



```
src/
└── app/
├── components/
│ ├── emoji-search/
│ │ ├── emoji-search.component.ts   # Component logic
│ │ ├── emoji-search.component.html # UI template
│ │ └── emoji-search.component.scss # Styling
│ └── theme-picker/
│ ├── theme-picker.component.ts     # Theme toggle logic
│ ├── theme-picker.component.html   # Theme toggle UI
│ └── theme-picker.component.scss   # Theme styling
├── services/
  └── emoji.service.ts              # Emoji data service
```

## 🚀 Running the Project

Install Angular CLI if you haven't:

```bash
npm install -g @angular/cli
```

Install dependencies and serve:

```bash
npm install
ng serve
```

Visit `http://localhost:4200` to see the custom directives in action.

---

## 🔗 Author
Made with ❤️ by
Muhammad Ahmad
