# 💰 Loan EMI Calculator

A professional, interactive Loan EMI Calculator built with **React** and **Vite**.
Calculate your monthly instalments instantly with beautiful charts and detailed breakdowns.

## 🌐 Live Demo
👉 [View Live](https://emi-calculator.vercel.app)

---

## ✨ Features

- 🎯 **Real-time EMI calculation** — updates instantly as you move sliders
- 📊 **Amortization chart** — year-wise principal vs interest bar chart
- 📅 **Amortization schedule** — full year-by-year repayment table
- 🔀 **Tenure comparison** — compare 5, 10, 15, 20 year plans side by side
- 📈 **Line chart** — see how EMI drops and interest rises with tenure
- 🎨 **Color-coded UI** — green for principal, red for interest, amber for total
- 📱 **Responsive design** — works on mobile and desktop
- ⚡ **Zero backend** — pure frontend, no API calls

---

## 🧮 EMI Formula Used
```
EMI = P × r × (1+r)ⁿ / ((1+r)ⁿ − 1)
```

Where:
- **P** = Principal loan amount
- **r** = Monthly interest rate (annual rate ÷ 12 ÷ 100)
- **n** = Total number of months (years × 12)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| React 18   | UI framework |
| Vite       | Build tool |
| Chart.js   | Bar & line charts |
| JavaScript | EMI logic & amortization |
| CSS-in-JS  | Inline styling |

---

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or above)
- npm

### Installation
```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/emi-calculator.git

# Go into the folder
cd emi-calculator

# Install dependencies
npm install

# Start development server
npm run dev
```

Open your browser at `http://localhost:5173`

### Build for production
```bash
npm run build
npm run preview
```

---

## 📁 Project Structure
```
emi-calculator/
├── src/
│   ├── App.jsx          # Main EMI Calculator component
│   ├── main.jsx         # React entry point
│   ├── App.css          # Global styles (cleared)
│   └── index.css        # Base styles (cleared)
├── public/
├── index.html
├── package.json
└── vite.config.js
```

---

## 📸 Screenshots

> Add your screenshots here after deployment!

---

## 🙋 About

Built as a **React learning project** for freshers.
Covers: `useState`, `useMemo`, `useEffect`, `useRef`, props, Chart.js integration.

---

## 📄 License

MIT License — free to use and modify.

---

⭐ If you found this helpful, give it a star!
```

---

## GitHub Topics / Tags

Add these in the **Topics** section of your repo (click the gear icon next to About):
```
react  vite  javascript  emi-calculator  loan-calculator  chartjs  frontend  beginner-project
```

---

## Commit Message for First Upload
```
feat: add Loan EMI Calculator with React, Chart.js, amortization schedule and tenure comparison
