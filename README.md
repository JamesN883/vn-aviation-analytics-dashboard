# Vietnam Aviation Analytics Dashboard

An interactive dashboard to explore flight trends, pricing patterns, and route coverage in Vietnam’s aviation sector.

## 📚 Table of Contents

1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Features](#features)
4. [Tools and Technologies](#tools-and-technologies)
5. [Dashboard Workflow](#dashboard-workflow)
6. [Installation and Setup](#installation-and-setup)

## 🚀 Introduction <a name="introduction"></a>

**Aevion** provides an interactive platform to analyze Vietnam’s aviation trends.  
Users can filter and visualize data across:

- 📍 Airlines
- 📍 Airports (departure/arrival)
- 📍 Specific time ranges

Visualizations include:

- 📊 Flight volume by airline (bar chart)
- 🔥 Density of flights by hour (heatmap)
- 🌍 Flight route coverage (geo-map)
- 💸 Ticket pricing trends (scatter plot)

## 📌 Objective <a name="objective"></a>

- Provide comprehensive insights into flight schedules, pricing, and routes
- Empower users to optimize travel and budget decisions
- Enhance data-driven planning for stakeholders
- Deliver a smooth and intuitive visualization experience

## ✅ Features <a name="features"></a>

### Visualization Tools
- **Bar Chart** – Flight volume by airline  
- **Heatmap** – Hourly flight density  
- **Scatter Plot** – Ticket price trends  
- **Geo Map** – Route and passenger flows  

### Filters & Metrics
- Filter by **airline**, **location**, or **date**
- Summary metrics: total flights, total passengers

## 🛠️ Tools and Technologies <a name="tools-and-technologies"></a>

### Development
- React, TypeScript, Vite
- D3.js for dynamic charts
- HTML & CSS

### Data Processing
- Python (Colab)
- Tableau (UI prototyping)

### 🔧 Project Management
- GitHub Desktop (version control)

## 📊 Dashboard Workflow <a name="dashboard-workflow"></a>

### Step 1: Overview and Navigation
- Navigate via a left-hand sidebar
- Explore aviation metrics through an interactive, responsive layout

### Step 2: Data Filtering
- Customize views by selecting airline, departure/arrival locations, and date ranges
- Instantly update visualizations to reflect your selections

### Step 3: Insight Extraction
- Compare flight volumes across airlines
- Track ticket price trends over time
- Identify peak hours and high-density routes

### Step 4: Strategic Planning
- Leverage historical trends to forecast demand
- Optimize travel plans and operations with data-driven insights

![image](https://github.com/user-attachments/assets/64b3e99f-ccd3-46de-bb4d-f5736ffbd2ab)

## 🚀 Installation and Setup <a name="installation-and-setup"></a>

### Prerequisites
1. **Node.js**: Ensure Node.js is installed for package management.
2. **Git**: Install Git for version control.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/tranphan2910/DSDV-VietnamAviationAnalytics-Web.git
   ```
2. Navigate to the project directory:
   ```bash
   cd DSDV-VietnamAviationAnalytics_InteractiveWeb\Code Project
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and navigate to `http://localhost:5173/`
