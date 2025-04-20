# Revenue Intelligence Platform

A lightweight forecasting system that predicts **revenue**, **churn**, **CAC**, and **LTV** using **Google Trends data** and **machine learning**. Built as a modular tool to help founders and investors make smarter, data-driven decisions — without needing a full data team.

> Most startup forecasts are static spreadsheets and hopeful guesses. This platform brings external demand signals into the model to simulate financial outcomes in real time.

---

## Features

- ✅ Forecasts key SaaS metrics with **Prophet** (Facebook’s open-source time-series model)
- 🔍 Uses **Google Trends** data as external regressors to improve accuracy
- 📊 Outputs include revenue, churn, CAC, LTV forecasts
- 🧠 Achieved **<10% MAPE** (Mean Absolute Percentage Error)
- 💼 Designed to be used by founders, operators, and VCs
- ⚙️ Easy to extend into a SaaS product, data consulting offer, or forecasting template

---

## 🧪 How It Works

1. **Collect Google Trends Data**
   - Pulls normalized keyword demand related to your industry or niche.

2. **Preprocess the Data**
   - Formats it into a Prophet-compatible format with regressors.

3. **Train the Model**
   - Uses Prophet + external regressors (e.g. Google Trends) for smarter predictions.

4. **Generate Forecasts**
   - Simulates future demand and outputs financial metrics.

---

## 📁 Repo Structure

