# 📊 Insurance Analytics Dashboard

> **IBM Cognos Live + Real-Time Insurance Analytics Dashboard**

An interactive insurance analytics dashboard designed to visualize key insurance metrics, claims data, policy performance, fraud cases, and agent performance through a clean web-based interface with **IBM Cognos Analytics integration**.

The dashboard combines **KPI cards, interactive charts, filtering, agent performance tables, and an embedded IBM Cognos dashboard** to provide a centralized view of insurance-related analytics.

## ✨ Features

### 📈 Insurance KPIs

The dashboard displays key performance indicators including:

* Total Active Policies
* Claims This Month
* Average Settlement Days
* Fraud Cases Flagged
* Overall Performance Rating
* Overall Customer Satisfaction Score

### 📊 Data Visualizations

The dashboard includes multiple Chart.js visualizations:

* **Claims by Policy Type** — Health, Life, Motor and Property
* **Monthly Claims Trend**
* **Claim Status** — Settled, Pending and Rejected
* **Agent Performance** — Performance and satisfaction scores

### 🔎 Interactive Filters

Users can filter the dashboard based on:

* Policy Type
* Agent Branch

A **Refresh Data** option is also provided to update the displayed dashboard values.

### 👥 Agent Performance

The dashboard provides a table containing:

| Metric             | Description                   |
| ------------------ | ----------------------------- |
| Agent Name         | Insurance agent identifier    |
| Performance Rating | Average agent performance     |
| Satisfaction Score | Average customer satisfaction |

### 🏢 IBM Cognos Integration

An embedded **IBM Cognos Live Analytics** dashboard is included directly inside the application using an iframe, allowing the project to combine the custom web dashboard with Cognos analytics.

## 🔐 Login Interface

The application includes a login screen with:

* Username
* Password
* Sign-in validation
* Session-based authentication
* Logout functionality

Authentication state is maintained using browser `sessionStorage`.

## 🛠️ Technologies Used

| Technology               | Purpose                                 |
| ------------------------ | --------------------------------------- |
| **HTML5**                | Application structure                   |
| **CSS3**                 | Dashboard styling and responsive layout |
| **JavaScript**           | Application logic and interactions      |
| **Chart.js**             | Data visualization                      |
| **IBM Cognos Analytics** | Embedded analytics dashboard            |
| **Font Awesome**         | Interface icons                         |
| **Google Fonts**         | Typography                              |
| **SessionStorage API**   | Session authentication                  |

Chart.js, Font Awesome and Google Fonts are loaded through external CDNs.

## 📂 Project Structure

```text
Insurance-Analytics/
│
├── index.html
└── README.md
```

The current implementation is contained in a single HTML file with embedded CSS and JavaScript.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/insurance-analytics.git
```

### 2. Open the project

Open the project directory and launch:

```text
index.html
```

You can also use **VS Code Live Server** for local development.

### 3. Login

Enter a username and password and click **Sign In** to access the dashboard.

> **Note:** The current authentication implementation is a frontend demonstration. It checks that username and password fields are populated and stores the authentication state in `sessionStorage`; it is not a production-grade secure authentication system.

## 📊 Dashboard Data

The current project contains demonstration insurance data including:

* 1,493 active policies
* Claims by policy type
* Monthly claim trends
* Settled, pending and rejected claims
* Fraud case counts
* Agent performance ratings
* Customer satisfaction scores

The **Refresh Data** functionality generates updated demonstration values using JavaScript rather than retrieving new data from an external database.

## 🎯 Project Objectives

The project demonstrates how insurance data can be transformed into an interactive analytics dashboard by combining:

* KPI monitoring
* Data visualization
* Claims analysis
* Agent performance analysis
* Filtering
* Business intelligence
* IBM Cognos integration

## 🔮 Future Improvements

Potential improvements include:

* 🔐 Secure backend authentication
* 🗄️ Database integration
* 📡 Real-time insurance data
* 🤖 AI-based fraud detection
* 📈 Advanced predictive analytics
* 🔍 More advanced dashboard filters
* 📊 Additional Cognos visualizations
* ☁️ Cloud deployment
* 📱 Enhanced mobile responsiveness
* 📤 Report and dashboard export

## 🎓 Project Type

**Data Analytics / Business Intelligence / Dashboard Development Project**

Built to explore insurance data visualization, KPI monitoring, business analytics and integration with **IBM Cognos Analytics**.

## 👨‍💻 Author

**Sankara Narayanan R R**

GitHub: `SankaraNarayanan-007`

---

⭐ **If you found this project useful, consider giving the repository a star!**
