# 🎓 Attendance Hub

A zero-backend, client-side web application designed to help students effortlessly track their college attendance, visualize data, and predict future class requirements to maintain academic thresholds. 

Built with a premium dark-mode UI, glassmorphism effects, and fully responsive mobile-first design.

## ✨ Features

* **Smart Data Parsing:** No manual data entry required. Simply copy and paste the raw attendance table directly from your college portal, and the regex engine extracts subjects, codes, and attendance numbers automatically.
* **Predictive Insights (75% Rule):** The algorithm calculates exactly how many consecutive classes you need to attend to recover a failing percentage, or how many you can safely afford to skip without dropping below the 75% threshold.
* **Aggregate Overview:** Automatically compiles total present and absent classes across all subjects to provide a master overview of your semester standing.
* **Beautiful Visualizations:** Utilizes `Chart.js` for clean, animated doughnut charts that dynamically adapt their color scheme based on your safety status (Green = Safe, Red = Danger).
* **100% Serverless & Zero-Cost:** Everything runs locally in the browser. There is no database or backend required, making it perfect for free static hosting on AWS S3, GitHub Pages, or Vercel.
* **Mobile-First Design:** Fluid typography, smart vertical stacking, and strict layout boundaries ensure the dashboard looks and feels like a native mobile app on any device.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (CSS Grid, Flexbox, Custom Properties)
* **Logic:** Vanilla JavaScript (ES6+)
* **Data Visualization:** [Chart.js](https://www.chartjs.org/) via CDN
* **Typography:** Inter Font Family 

## 🚀 How to Use

1. Clone the repository or simply download the `index.html` file.
2. Open the file in any modern web browser.
3. Copy your current attendance table from your student portal (including subject codes, names, total classes, etc.).
4. Paste the raw text into the input field and click **Generate Dashboard**.

## ☁️ Deployment

Because this project is a single static HTML file with no backend dependencies, it is highly optimized for ultra-low-cost cloud deployment. 

**Recommended Hosting:**
* AWS S3 (Static Website Hosting)
* AWS Amplify
* GitHub Pages

Deploying on S3 provides a robust, personal URL with monthly costs effectively rounding down to $0.00 under standard personal usage.
