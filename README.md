# 🚀 Smart Energy Monitoring Dashboard

An interactive web dashboard for real-time energy monitoring, cost optimization, and sustainability analytics in industrial environments.

🔗 **Live Demo:** https://smart-energy-dashboard-pvvs.vercel.app  
💻 **Source Code:** https://github.com/naisha-khan/smart-energy-dashboard

---


## 📊 Project Overview

The **Smart Energy Monitoring Dashboard** is a web-based analytics platform designed to simulate energy management in industrial facilities. It provides real-time monitoring of power consumption, renewable energy utilization, operational costs, and environmental impact through interactive visualizations.

The project demonstrates how software and data visualization can help industries improve energy efficiency, reduce costs, and track sustainability goals.

---


## 🎯 Why I Built This Project

With industries increasingly focusing on **energy efficiency**, **digital transformation**, and **sustainability**, energy analytics platforms have become critical for decision-making.

I built this project to explore how modern dashboards can transform raw energy data into actionable insights for:
- Reducing energy wastage
- Improving power distribution
- Increasing renewable energy adoption
- Monitoring carbon footprint

---


## ✨ Features
### 🔋 Real-Time Energy Monitoring
- Live energy consumption tracking (kW)
- Hourly and daily trend visualization
- Peak load detection
- Transformer load monitoring
- Power quality indicators

### 🌱 Sustainability Analytics
- Renewable energy contribution tracking
- Solar / wind / grid energy mix visualization
- CO₂ emission estimation
- Carbon footprint analytics
- Environmental impact metrics

### 🚨 Smart Alert System
- High-load warnings
- Overutilization alerts
- Equipment anomaly notifications
- Load balancing recommendations

### 💰 Cost Optimization
- Energy cost calculation using tariff-based pricing
- Monthly expenditure estimation
- Renewable vs grid cost comparison
- Budget variance tracking

---


## 📊 Business Impact (Simulated)

Based on simulated industrial energy usage data, the dashboard demonstrates potential for:

- Up to **15% reduction in energy costs** through optimization
- Better utilization of renewable energy sources
- Improved visibility into peak load conditions
- Enhanced sustainability reporting through carbon tracking

---


## 🛠️ Technology Stack
### Frontend
- HTML5
- CSS3
- JavaScript (ES6+)

### UI / Styling
- Tailwind CSS
- Custom animations
- Responsive design

### Data Visualization
- Chart.js

### Additional Tools
- Font Awesome
- Vercel (Deployment)

---


## 🏗️ Architecture
The dashboard simulates data from multiple energy-related sources:

### Data Sources
- Industrial IoT Sensors  
- Smart Energy Meters  
- Renewable Energy Sources  
- Grid Power Systems  
- Billing / Cost Analytics  

### Processing Pipeline
```text
Sensor Data → Processing Layer → Analytics Engine → Dashboard Visualization
```

Raw energy readings are processed into:
- Consumption analytics
- Cost calculations
- Efficiency metrics
- Sustainability insights

---


## 📐 Core Metrics & Calculations

### Energy Cost Calculation
```javascript
monthlyCost = monthlyConsumption * tariffRate
```

### CO₂ Emission Estimation
```javascript
co2Emissions = energyConsumption * emissionFactor
```

### Renewable Energy Contribution
```javascript
renewablePercentage = (renewableEnergy / totalEnergy) * 100
```

These calculations help estimate:
- Monthly operational cost
- Environmental impact
- Energy efficiency

---

## 🚀 Deployment

This project is deployed on **Vercel**.

🔗 **Production URL:**  
https://smart-energy-dashboard-pvvs.vercel.app

---


## 💻 Local Setup

### Clone Repository
```bash
git clone https://github.com/naisha-khan/smart-energy-dashboard.git
cd smart-energy-dashboard
```

### Run Locally
Since this is a frontend-only project:

```bash
open index.html
```

Or use a local server:

```bash
python -m http.server 8000
```

OR

```bash
npx serve .
```

---


## 🔮 Future Improvements

Potential enhancements for future versions:

- Real IoT sensor integration
- Backend API for live data streaming
- ML-based predictive maintenance
- AI-powered anomaly detection
- Energy demand forecasting
- Role-based enterprise dashboards

---


## 📄 License

This project is licensed under the MIT License.
