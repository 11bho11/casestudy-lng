# 🌍 Global LNG Production & Contract Modelling System  - A Python Case Study

> ⚠️ This repository shares my learnings in building and designing software architecture.  

## 📌 Overview

This project documents the architecture and design of a Python-based modelling system built to represent global LNG production and long-term contract flows at:

- Region/country level   
- Liquefaction plant & train level  
- Project ownership level    
- Aggregated level  

The system was designed to support forward-looking commercial analysis, supply forecasting, and scenario modelling.


---

## 🎯 Problem Context

Commercial LNG analysis typically requires modelling:

- Multi-train liquefaction facilities  
- Ownership structures across multiple shareholders  
- Long-term take-or-pay contracts  
- Regional and country-level aggregation  
- Portfolio-level exposure analysis  


This project aimed to design a **scalable, extensible modelling engine in Python** that mirrors how LNG markets operate structurally.

---

## 🏗 System Architecture

The model was structured hierarchically:
<img width="1610" height="880" alt="image" src="https://github.com/user-attachments/assets/56ebeb47-de4a-492d-ac35-0b239a125709" />

