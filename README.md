# 🚗 Dynamic Pricing for Urban Parking Lots

**Capstone Project – Summer Analytics 2025**  
_Consulting & Analytics Club × Pathway, IIT Guwahati_

---

## 📌 Overview

This project builds a **real-time dynamic pricing engine** for urban parking lots using streaming data. The system adjusts prices based on occupancy, traffic, events, queue length, vehicle type, and nearby competition — helping optimize space usage and reduce congestion.

Built using **NumPy**, **Pandas**, **Pathway**, and **Bokeh**, all logic is implemented from scratch in Python.

---

## 📂 Dataset Summary

- 14 parking lots, 73 days, 18 time intervals/day  
- Includes: Occupancy, Queue, Location, Vehicle Type, Traffic, Special Days

---

## 🎯 Objective

- Start from a base price of $10  
- Dynamically adjust prices based on real-time data  
- Ensure smooth and explainable price variations  

---

## 🧠 Models Implemented

### ✅ Model 1: Baseline Linear Model  
Simple price adjustment based on occupancy

### ✅ Model 2: Demand-Based Model  
Price based on a weighted demand function using multiple features

### ⚙️ Model 3: Competitive Pricing (Optional)  
Factors in nearby lot prices and rerouting logic

---

## 🛠 Tools Used

- **Python**, **Pandas**, **NumPy**  
- **Pathway** – Real-time data streaming  
- **Bokeh** – Interactive live visualizations

---

## 📊 Visualizations

- Real-time pricing plots per lot  
- Competitor price comparisons  
- Demand vs. Price trends

---

## 📑 Assumptions

- Demand rises with occupancy and queue length  
- Traffic congestion and vehicle type affect pricing  
- Special days increase demand

---

## 📝 Submission Includes

- Well-documented Colab notebook  
- Real-time visualizations using Bokeh  
- Detailed report with models, assumptions, and results

---
