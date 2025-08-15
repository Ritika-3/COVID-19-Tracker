COVID-19 Tracker

A React-based web application that provides real-time COVID-19 statistics globally and for individual countries. It fetches live data from a public API and visualizes it using responsive components and charts.

🌐 Live Demo → covid-19-tracker-bc6a3.web.app

📜 Features

Global Summary: Total confirmed cases, recoveries, and deaths.

Country-Specific Data: Search and view stats for any country.

Interactive Charts: Graphical representation of cases over time.

Real-Time Updates: Data fetched from a live COVID-19 API.

Responsive Design: Optimized for desktop and mobile devices.

🛠️ Tech Stack

React.js – UI framework

Material-UI – Styling and components

Chart.js – Data visualization

Axios / Fetch API – Data fetching

Public COVID-19 API – Data source (e.g., disease.sh or similar)

📂 Project Structure
COVID-19-Tracker-master/
├── public/
│   ├── index.html
│   └── favicon.ico
├── src/
│   ├── components/     # Reusable UI components
│   ├── App.js          # Main app logic
│   ├── App.css         # Global styles
│   ├── index.js        # React entry point
│   └── api.js          # API calls
├── package.json
└── README.md

🚀 Getting Started
1. Clone the repository
git clone https://github.com/<your-username>/COVID-19-Tracker.git
cd COVID-19-Tracker-master

2. Install dependencies
npm install

3. Start development server
npm start


Then open http://localhost:3000 in your browser.

4. Build for production
npm run build

🎯 How to Use

Launch the app in your browser.

View global stats on the homepage.

Select a country from the dropdown to view its data.

Check the charts for visual trends over time.

📊 Example Metrics
Metric	Example Value
Confirmed	120,345,678
Recovered	95,432,100
Deaths	2,543,210
Updated	16-Aug-2025 14:35 UTC
🤝 Contributing

Fork this repository.

Create a feature branch.

Commit changes and push.

Open a Pull Request.
