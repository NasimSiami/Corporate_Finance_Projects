# Event Study: The Market Reaction to Earnings Announcements

This project applies **event study methodology** to measure the market's reaction to quarterly earnings announcements. By leveraging security price data, the analysis quantifies abnormal stock returns around the announcement date to determine the **information content of earnings releases**.

## 📌 Overview

Using a sample of U.S. firms, this notebook investigates whether earnings surprises significantly impact stock prices. The methodology is inspired by academic frameworks like those presented by A. Craig MacKinlay and involves:

- Identifying event dates (earnings announcements)
- Defining event and estimation windows
- Estimating expected (normal) returns using a **market model**
- Calculating **abnormal returns (ARs)** and **cumulative abnormal returns (CARs)**
- Comparing market responses across three earnings news types: **good**, **bad**, and **neutral**

## 🔍 Methods Used

- Ordinary Least Squares (OLS) regression for estimating normal returns
- Cumulative Abnormal Return (CAR) computation
- Event-time indexing and aggregation across firms
- Visualization of CAR patterns across time

## 📊 Key Findings

- **Good news** firms show significant positive CARs on and after announcement days.
- **Bad news** firms show significant negative CARs.
- **Neutral news** firms do not display significant abnormal returns.
- Results are consistent with semi-strong form market efficiency: new information is rapidly incorporated into stock prices.

## 📚 Reference

- A. Craig MacKinlay (1997), *Event Studies in Economics and Finance*, Journal of Economic Literature.

## 💡 Why It Matters

Event studies are essential tools in **financial economics, accounting, and law**. This project demonstrates how such a study can be implemented using Python and real-world data, making it a valuable reference for analysts and students alike.
