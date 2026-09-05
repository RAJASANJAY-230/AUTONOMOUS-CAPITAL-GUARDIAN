Autonomous portfolio risk-control system that detects market shocks, evaluates multi-dimensional risk, optimizes asset allocation, and performs constraint-aware simulated rebalancing.
# 🛡️ Autonomous Capital Guardian

**Detect • Decide • Protect • Rebalance**

Autonomous Capital Guardian is a FinTech risk-control and portfolio optimization system designed to continuously monitor portfolio risk, detect simulated market shocks, and automatically determine a constrained response.

Instead of simply detecting and reporting risk, the system closes the control loop:

**Sense → Assess → Decide → Optimize → Rebalance → Verify**

## 🚀 Key Features

- Multi-dimensional portfolio risk assessment
- VaR and Expected Shortfall analysis
- Volatility and drawdown monitoring
- Concentration and liquidity risk evaluation
- Simulated market-shock detection
- Risk-state based control logic
- Constraint-aware portfolio optimization
- Automated simulated rebalancing
- Safety guardrails for capital protection
- Explainable autonomous decisions
- Autonomous and human-approval modes
- Before/after risk verification
- Scenario-based market simulation

## 🧠 Risk Control

| Risk State | Risk Score | Action |
|---|---:|---|
| 🟢 LOW | < 40 | No Action |
| 🟡 MODERATE | 40–60 | Monitor |
| 🟠 HIGH | 60–75 | Rebalance |
| 🔴 CRITICAL | > 75 | Defensive De-risk |

## ⚙️ Optimization

The optimizer seeks a risk-adjusted allocation while controlling unnecessary portfolio turnover:

`Optimal Allocation = argmax(Return − λ·Risk − k·Turnover)`

Subject to allocation limits, minimum cash reserves, liquidity constraints, maximum turnover, and transaction-cost considerations.

## 🏗️ Architecture

Simulated Market Data  
↓  
Market Intelligence  
↓  
Risk Engine  
↓  
Shock Detector  
↓  
Control Engine  
↓  
Optimization Engine  
↓  
Simulated Rebalancer  
↓  
Risk Verification  
↓  
Decision Dashboard

## 💻 Technology Stack

- **Frontend:** React + TypeScript
- **Backend:** FastAPI + Python
- **Financial Computing:** NumPy + Pandas + SciPy
- **Database:** SQLite
- **Data:** Synthetic / simulated market data

## 🎯 Project Goal

Transform traditional reactive risk monitoring into an autonomous capital-protection loop that can **detect risk, make an explainable decision, optimize the response, rebalance within predefined guardrails, and verify the resulting risk state.**

> ⚠️ This is an educational/hackathon prototype using simulated data. No real financial transactions are executed and the system does not provide financial advice.
