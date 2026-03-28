<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=200&section=header&text=FinTrack%20AI&fontSize=80&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=UPI%20Spend%20Analyzer%20%7C%20Behavioral%20Intelligence%20for%20Indian%20Payments&descAlignY=60&descSize=16" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=6C63FF&center=true&vCenter=true&width=600&lines=UPI+Spend+Analyzer;Behavioral+Finance+Intelligence;AI-Powered+Money+Insights;Built+for+India+%F0%9F%87%AE%F0%9F%87%B3" alt="Typing SVG" />

<br/><br/>

<a href="https://fintrack-ai-upi-spend-analyzer.streamlit.app/" target="_blank">
  <img src="https://img.shields.io/badge/🚀%20LIVE%20DEMO-Click%20Here-6C63FF?style=for-the-badge&logoColor=white" alt="Live Demo"/>
</a>
&nbsp;
<img src="https://img.shields.io/badge/Python-3.12+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Groq-AI%20Powered-00A67E?style=for-the-badge&logoColor=white"/>

<br/><br/>

<img src="https://img.shields.io/badge/Status-Live%20%26%20Running-4ECDC4?style=for-the-badge"/>
&nbsp;
<img src="https://img.shields.io/badge/Made%20for-India%20🇮🇳-FF9933?style=for-the-badge"/>
&nbsp;
<img src="https://img.shields.io/badge/UPI%20Apps-GPay%20|%20PhonePe%20|%20Paytm-6C63FF?style=for-the-badge"/>
&nbsp;
<img src="https://img.shields.io/badge/Privacy-100%%20Local-green?style=for-the-badge"/>

<br/><br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

</div>

<br/>

## 📌 Quick Links

<div align="center">

| 🚀 [Live Demo](https://fintrack-ai-upi-spend-analyzer.streamlit.app/) | ❓ [Problem Statement](#-problem-statement) | 💡 [Solution](#-solution) |
|:---:|:---:|:---:|
| 🏗️ [Architecture](#-system-architecture) | ✨ [Features](#-features) | 🛠️ [Tech Stack](#%EF%B8%8F-tech-stack) |
| ⚡ [Quick Start](#-quick-start) | 📁 [File Structure](#-file-structure) | 🗺️ [Roadmap](#%EF%B8%8F-roadmap) |

</div>

<br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<br/>

## ❓ Problem Statement

<div align="center">

```
India has 500M+ UPI users conducting billions of transactions monthly.
Yet there is ZERO native tooling to understand where digital money goes.
```

</div>

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#FF6B6B', 'lineColor': '#6C63FF', 'secondaryColor': '#16213e', 'tertiaryColor': '#0f0f1a', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'nodeBorder': '#6C63FF', 'clusterBkg': '#16213e', 'titleColor': '#E0E0F0', 'edgeLabelBackground': '#1a1a2e', 'fontFamily': 'monospace'}}}%%
flowchart LR
    subgraph PAIN ["🚨 The Pain Points"]
        direction TB
        A["🌑 Zero Visibility\nPeople tap UPI 30–50x/month\nbut can't track spending"]
        B["🔀 Multi-App Chaos\nGPay + PhonePe + Paytm\n= duplicate messy records"]
        C["📉 No Early Warnings\nOverspending discovered\nonly after month ends"]
        D["🧾 Subscription Leaks\n₹3,000–₹8,000/year\nsilently drained"]
        E["📊 No Benchmarks\nNo way to know if\nyour spend is normal"]
    end

    subgraph SCALE ["📈 Scale of Problem"]
        direction TB
        F["500M+\nUPI Users"]
        G["₹6L Crore\nMonthly UPI Volume"]
        H["< 5% Users\nTrack Spending"]
        I["₹0 Solutions\nBuilt for This Gap"]
    end

    PAIN --> SCALE

    style A fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999
    style B fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style C fill:#1a2d1a,stroke:#FF9F43,color:#FFB673
    style D fill:#1a1a2d,stroke:#A29BFE,color:#C4C0FF
    style E fill:#2d1a2d,stroke:#FF6B6B,color:#FF9999
    style F fill:#1a1a2e,stroke:#6C63FF,color:#6C63FF
    style G fill:#1a1a2e,stroke:#4ECDC4,color:#4ECDC4
    style H fill:#1a1a2e,stroke:#FF6B6B,color:#FF6B6B
    style I fill:#1a1a2e,stroke:#FFD93D,color:#FFD93D
    style PAIN fill:#0f0f1a,stroke:#FF6B6B,stroke-width:2px,color:#E0E0F0
    style SCALE fill:#0f0f1a,stroke:#6C63FF,stroke-width:2px,color:#E0E0F0
```

**The core problems are:**

| # | Problem | Impact |
|---|---------|--------|
| 🌑 | **Invisible spending** — UPI removes friction from paying, also from overspending | No moment of reflection before or after a transaction |
| 🔀 | **Multi-app fragmentation** — 2–3 UPI apps per person, impossible to reconcile | Duplicate entries inflate real spending figures |
| 📊 | **No behavioral intelligence** — Banks show raw lists, not patterns | Users never discover their own spending personality |
| 🧾 | **Subscription blindness** — Recurring charges accumulate silently | Most users can't name all active subscriptions |
| 📉 | **Reactive, not proactive** — No early-warning system exists | Budget awareness comes only after damage is done |
| 🏦 | **No benchmarking** — Can't compare your ₹8,000/month food spend to peers | No context to know if you're disciplined or excessive |

<br/>

## 💡 Solution

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#6C63FF', 'lineColor': '#4ECDC4', 'secondaryColor': '#16213e', 'tertiaryColor': '#0f0f1a', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'nodeBorder': '#4ECDC4', 'clusterBkg': '#16213e', 'titleColor': '#E0E0F0', 'edgeLabelBackground': '#1a1a2e', 'fontFamily': 'monospace'}}}%%
flowchart TD
    TITLE(["💸 FinTrack AI\nComplete UPI Intelligence Platform"])

    subgraph SOLUTION ["✅ What FinTrack AI Solves"]
        direction LR
        S1["🎯 Budget Tracker\nLive burn-rate +\nbreach projection"]
        S2["🔮 Spend Forecast\nARIMA/ETS with\nconfidence bands"]
        S3["🏦 Multi-Account\nMerge + deduplicate\nacross all apps"]
        S4["🔍 Anomaly Alerts\n6 detection methods\nZ-score · IQR · more"]
        S5["🤖 AI Advisor\nFree Groq API\nLlama 3.3 70B chat"]
        S6["📈 Peer Benchmarks\nIndia city-tier\ncomparison engine"]
    end

    TITLE --> SOLUTION

    style TITLE fill:#6C63FF,stroke:#4ECDC4,stroke-width:3px,color:#fff,font-size:16px
    style S1 fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style S2 fill:#1a1a2d,stroke:#6C63FF,color:#A29BFE
    style S3 fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style S4 fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999
    style S5 fill:#1a2d1a,stroke:#00A67E,color:#00D4A0
    style S6 fill:#2d1a2d,stroke:#FF9F43,color:#FFB673
    style SOLUTION fill:#0f0f1a,stroke:#4ECDC4,stroke-width:2px,color:#E0E0F0
```

FinTrack AI is a **fully local, open-source Streamlit dashboard** that transforms raw UPI CSV exports into actionable financial intelligence. Works with every major UPI app, requires no backend server, sends no raw data anywhere, and gives you fintech-grade analysis — completely free.

<br/>

## 🏗️ System Architecture

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#6C63FF', 'lineColor': '#6C63FF', 'secondaryColor': '#16213e', 'tertiaryColor': '#0f0f1a', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'clusterBkg': '#111128', 'titleColor': '#E0E0F0', 'edgeLabelBackground': '#1a1a2e', 'fontFamily': 'monospace'}}}%%
flowchart TD
    subgraph INPUT ["📤 Layer 1 — Data Ingestion"]
        direction LR
        GP["📱 Google Pay\nCSV Export"]
        PP["📲 PhonePe\nCSV Export"]
        PT["💳 Paytm\nCSV Export"]
        BH["🏦 BHIM / Bank\nCSV Export"]
        EX["➕ Extra Accounts\nMulti-upload sidebar"]
    end

    subgraph PIPELINE ["⚙️ Layer 2 — Processing Pipeline"]
        direction LR
        PA["📄 parser.py\n11 date formats\n4 UPI format maps\nAuto column detection"]
        DD["🔁 deduplicator.py\nFuzzy match RapidFuzz\nAmount ±₹1 · Date ±1 day\nScore threshold ≥72"]
        CA["🏷️ categorizer.py\nKeyword reverse index\n12 categories\n300+ keywords"]
        AN["🔍 anomaly_detector.py\nZ-Score · IQR · Odd Hour\nRound Num · New Merchant\nFrequency Spike"]
    end

    subgraph ANALYTICS ["🧠 Layer 3 — Analytics Engines"]
        direction LR
        IN["📊 insights.py\nMoM trend\nSubscriptions\nSavings · Velocity\nBehavioral nudges"]
        BT["🎯 budget_tracker.py\nBurn rate calc\nEOM projection\nBreach alerts\nStatus labeling"]
        FC["🔮 forecaster.py\nAuto-ARIMA\nHolt-Winters ETS\nLinear fallback\n80% confidence bands"]
        BM["📈 benchmarks.py\nTier 1/2/3 data\nLow/Mid/High bracket\nRatio vs peers\nSavings benchmark"]
        AI["🤖 ai_advisor.py\nGroq API\nLlama 3.3 70B\nMulti-turn chat\nContext injection"]
    end

    subgraph CHARTS ["📊 Layer 4 — Visualization"]
        direction LR
        CH["📉 charts.py\n8 Plotly builders\nDark theme\nCategory donut\nAnomaly scatter\nCalendar heatmap\nSavings gauge"]
    end

    subgraph DASHBOARD ["🖥️ Layer 5 — 10-Page Streamlit Dashboard  (app.py)"]
        direction LR
        P1["📊 Overview"]
        P2["🏷️ Categories"]
        P3["🔍 Anomalies"]
        P4["🧠 Insights"]
        P5["🎯 Budget"]
        P6["🔮 Forecast"]
        P7["🏦 Multi-Acct"]
        P8["🤖 AI Advisor"]
        P9["📈 Benchmarks"]
        P10["📋 Transactions"]
    end

    INPUT --> PIPELINE
    PA --> DD --> CA --> AN
    PIPELINE --> ANALYTICS
    ANALYTICS --> CHARTS
    CHARTS --> DASHBOARD

    style GP fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE
    style PP fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE
    style PT fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE
    style BH fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE
    style EX fill:#16213e,stroke:#6C63FF,color:#6C63FF,stroke-dasharray:5

    style PA fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style DD fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style CA fill:#2d1f1a,stroke:#FF9F43,color:#FFB673
    style AN fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999

    style IN fill:#1a1a2e,stroke:#A29BFE,color:#C4C0FF
    style BT fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style FC fill:#1a1a2d,stroke:#6C63FF,color:#A29BFE
    style BM fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style AI fill:#1a2d22,stroke:#00A67E,color:#00D4A0

    style CH fill:#16213e,stroke:#FF9F43,color:#FFB673

    style P1 fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE
    style P2 fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style P3 fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999
    style P4 fill:#2d1f1a,stroke:#FF9F43,color:#FFB673
    style P5 fill:#1a2d22,stroke:#00A67E,color:#00D4A0
    style P6 fill:#1a1a2d,stroke:#A29BFE,color:#C4C0FF
    style P7 fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style P8 fill:#1a2d22,stroke:#00A67E,color:#00D4A0
    style P9 fill:#2d1a2d,stroke:#FF6B6B,color:#FF9999
    style P10 fill:#1a1a2e,stroke:#6C63FF,color:#A29BFE

    style INPUT fill:#0a0a18,stroke:#6C63FF,stroke-width:2px,color:#E0E0F0
    style PIPELINE fill:#0a0a18,stroke:#4ECDC4,stroke-width:2px,color:#E0E0F0
    style ANALYTICS fill:#0a0a18,stroke:#FF9F43,stroke-width:2px,color:#E0E0F0
    style CHARTS fill:#0a0a18,stroke:#FF6B6B,stroke-width:2px,color:#E0E0F0
    style DASHBOARD fill:#0a0a18,stroke:#A29BFE,stroke-width:2px,color:#E0E0F0
```

<br/>

### 🔄 Module Interaction Map

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#6C63FF', 'lineColor': '#4ECDC4', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'clusterBkg': '#111128', 'titleColor': '#E0E0F0', 'edgeLabelBackground': '#1a1a2e', 'fontFamily': 'monospace'}}}%%
graph LR
    CSV["📄 CSV Files"] -->|parse_csv| PAR["parser.py\n📄"]
    PAR -->|raw DataFrame| DED["deduplicator.py\n🔁"]
    DED -->|clean DataFrame| CAT["categorizer.py\n🏷️"]
    CAT -->|+category +merchant| ANO["anomaly_detector.py\n🔍"]
    ANO -->|+anomaly_flags| INS["insights.py\n🧠"]
    ANO -->|+anomaly_flags| BUD["budget_tracker.py\n🎯"]
    ANO -->|+anomaly_flags| FOR["forecaster.py\n🔮"]
    ANO -->|+anomaly_flags| BEN["benchmarks.py\n📈"]
    ANO -->|+anomaly_flags| AIA["ai_advisor.py\n🤖"]
    INS & BUD & FOR & BEN & AIA -->|structured data| CHA["charts.py\n📉"]
    CHA -->|Plotly figures| APP["app.py\n🖥️ Dashboard"]
    GROQ["🟢 Groq API\nLlama 3.3 70B"] <-->|API call| AIA

    style CSV fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style PAR fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style DED fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style CAT fill:#2d1f1a,stroke:#FF9F43,color:#FFB673
    style ANO fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999
    style INS fill:#1a1a2e,stroke:#A29BFE,color:#C4C0FF
    style BUD fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style FOR fill:#1a1a2d,stroke:#6C63FF,color:#A29BFE
    style BEN fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style AIA fill:#1a2d22,stroke:#00A67E,color:#00D4A0
    style CHA fill:#2d1f1a,stroke:#FF9F43,color:#FFB673
    style APP fill:#6C63FF,stroke:#4ECDC4,stroke-width:3px,color:#fff
    style GROQ fill:#1a2d22,stroke:#00A67E,color:#00D4A0,stroke-dasharray:5
```

<br/>

### 🔍 Anomaly Detection Logic

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#FF6B6B', 'lineColor': '#FF6B6B', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'clusterBkg': '#111128', 'titleColor': '#E0E0F0', 'edgeLabelBackground': '#1a1a2e', 'fontFamily': 'monospace'}}}%%
flowchart TD
    TXN(["💳 Transaction\nEnters Pipeline"])

    TXN --> Z["Z-Score Check\n|z| > 2.5 threshold\n→ Globally unusual amount"]
    TXN --> IQR["IQR per Category\nQ3 + 2×IQR upper fence\n→ Outlier in category"]
    TXN --> OH["Odd Hour Check\n23:00 – 05:00 window\n→ Late-night impulse"]
    TXN --> RN["Round Number\nAmount ≥ ₹5,000\n+ multiple of 500/1000"]
    TXN --> NM["New Merchant\nFirst-ever transaction\nwith this vendor"]
    TXN --> FS["Frequency Spike\nDaily count > 2.5×\naverage daily rate"]

    Z & IQR & OH & RN & NM & FS --> SCORE["🧮 Anomaly Score\nCount all flags fired\n0 = Clean"]

    SCORE --> SEV{"Severity\nClassifier"}
    SEV -->|score = 0| CLEAN["✅ Clean"]
    SEV -->|score = 1| LOW["🟡 Low"]
    SEV -->|score = 2| MED["🟠 Medium"]
    SEV -->|score ≥ 3| HIGH["🔴 High"]

    style TXN fill:#6C63FF,stroke:#4ECDC4,color:#fff,stroke-width:2px
    style Z fill:#1a1a2e,stroke:#FF6B6B,color:#FF9999
    style IQR fill:#1a1a2e,stroke:#FF9F43,color:#FFB673
    style OH fill:#1a1a2e,stroke:#A29BFE,color:#C4C0FF
    style RN fill:#1a1a2e,stroke:#FFD93D,color:#FFE580
    style NM fill:#1a1a2e,stroke:#4ECDC4,color:#4ECDC4
    style FS fill:#1a1a2e,stroke:#FF6B6B,color:#FF9999
    style SCORE fill:#16213e,stroke:#6C63FF,color:#A29BFE,stroke-width:2px
    style SEV fill:#1a1a2e,stroke:#FFD93D,color:#FFE580
    style CLEAN fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style LOW fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style MED fill:#2d1f1a,stroke:#FF9F43,color:#FFB673
    style HIGH fill:#2d1a1a,stroke:#FF6B6B,color:#FF6B6B
```

<br/>

### 🔮 Forecasting Model Selection Logic

```mermaid
%%{init: {'theme': 'base', 'themeVariables': {'primaryColor': '#1a1a2e', 'primaryTextColor': '#E0E0F0', 'primaryBorderColor': '#6C63FF', 'lineColor': '#6C63FF', 'background': '#0f0f1a', 'mainBkg': '#1a1a2e', 'clusterBkg': '#111128', 'titleColor': '#E0E0F0', 'fontFamily': 'monospace'}}}%%
flowchart TD
    CAT(["📂 Category\nSelected"])
    CAT --> SERIES["📈 Build Monthly\nTime Series"]
    SERIES --> CHK{How many\nmonths of data?}

    CHK -->|"≥ 4 months"| ARIMA["🔬 Auto-ARIMA\nAuto-selects p,d,q\nAIC optimized\nStepwise search"]
    CHK -->|"3 months"| ETS["📊 Holt-Winters ETS\nExponential smoothing\nAdditive trend\nResidual std CI"]
    CHK -->|"< 3 months"| LINEAR["📏 Linear Trend\nPolyfit degree 1\n±20% uncertainty band\nFallback guaranteed"]

    ARIMA --> FAIL{Model\nconverged?}
    FAIL -->|Yes| OUT
    FAIL -->|No| LINEAR

    ETS --> OUT
    LINEAR --> OUT

    OUT(["📦 Output\npoint · lower_80 · upper_80\ntrend · narrative · method"])

    style CAT fill:#6C63FF,stroke:#4ECDC4,color:#fff
    style SERIES fill:#1a1a2e,stroke:#A29BFE,color:#C4C0FF
    style CHK fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style ARIMA fill:#1a2d1a,stroke:#4ECDC4,color:#4ECDC4
    style ETS fill:#1a1a2d,stroke:#6C63FF,color:#A29BFE
    style LINEAR fill:#2d1a1a,stroke:#FF6B6B,color:#FF9999
    style FAIL fill:#2d2a1a,stroke:#FFD93D,color:#FFE580
    style OUT fill:#16213e,stroke:#4ECDC4,stroke-width:2px,color:#4ECDC4
```

<br/>

## ✨ Features

<table>
<tr>
<td width="50%" valign="top">

### 📊 Core Analytics
- Auto-categorization into **12 spending categories** via keyword reverse index
- Merchant extraction with **30+ brand canonical name** mappings
- **Monthly trend** with MoM change line overlay
- **Day-of-week heatmap** and weekend vs weekday split
- **Spend calendar** — GitHub-style contribution heatmap

### 🎯 Budget Tracker
- Set monthly ₹ limits per category via inline editor
- Live **progress bars** with colour-coded status badges
- **Burn-rate projection** — *"At ₹450/day you'll exceed Food budget by ₹800 in 12 days"*
- Budget status persists in `st.session_state` across navigation
- Grouped bar: Spent vs Projected vs Budget limit

### 🏦 Multi-Account Deduplication
- Upload CSVs from **GPay + PhonePe + bank** simultaneously
- Detection: amount **±₹1**, date **±1 day**, description fuzzy score **≥72/100**
- Keeps richer description, excludes the duplicate
- Full dedup report: count removed, ₹ de-noised, source breakdown

</td>
<td width="50%" valign="top">

### 🔍 Anomaly Detection *(6 methods)*
- **Z-Score** — globally unusual transaction amounts
- **IQR per category** — outliers within each spend bucket
- **Odd-hour** — transactions between 11 PM and 5 AM
- **Round number** — suspicious large round amounts
- **New merchant** — first-ever transaction with vendor
- **Frequency spike** — abnormally high-activity days

### 🔮 Spend Forecasting
- Auto-selects best model: **ARIMA → ETS → Linear**
- **80% confidence intervals** rendered as error bars
- Per-category sparklines: history + forecast diamond
- Total forecast narrative in plain English

### 🤖 AI Financial Advisor *(Free)*
- **Groq API + Llama 3.3 70B** — no credit card needed
- Injects statistical summary as context, not raw transactions
- Multi-turn conversation with full history
- 8 one-click starter question chips
- Auto monthly financial health summary

</td>
</tr>
</table>

<br/>

## 🛠️ Tech Stack

<div align="center">

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **UI Framework** | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) | 10-page interactive dashboard |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | ETL, aggregation, time-series |
| **Visualization** | ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) | All interactive charts |
| **ML / Statistics** | ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) | Z-score, IQR anomaly detection |
| **Forecasting** | `statsmodels` + `pmdarima` | Auto-ARIMA · Holt-Winters ETS |
| **Fuzzy Matching** | `rapidfuzz` | Transaction deduplication |
| **AI / LLM** | ![Groq](https://img.shields.io/badge/Groq-Llama%203.3%2070B-00A67E?style=flat-square) | Free AI financial advisor |
| **Language** | ![Python](https://img.shields.io/badge/Python-3.12+-3776AB?style=flat-square&logo=python&logoColor=white) | Core runtime |
| **Deployment** | ![Streamlit Cloud](https://img.shields.io/badge/Streamlit%20Cloud-Live-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) | Public hosting |

</div>

<br/>

## ⚡ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/fintrack-ai-upi-spend-analyzer.git
cd fintrack-ai-upi-spend-analyzer

# 2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your free Groq API key (only needed for AI Advisor page)
#    Get your free key at https://console.groq.com — no credit card needed
mkdir -p .streamlit
echo 'GROQ_API_KEY = "gsk_your_key_here"' > .streamlit/secrets.toml

# 5. Launch the app
streamlit run app.py
```

Open **http://localhost:8501** — tick **"Use sample data"** in the sidebar for an instant demo without uploading anything.

<br/>

## 📁 File Structure

```
fintrack-ai-upi-spend-analyzer/
│
├── 📄 app.py                        # Main Streamlit dashboard — 10 pages
├── 📋 requirements.txt              # Dependencies (flexible version bounds)
├── 📖 README.md                     # This file
├── 🐍 runtime.txt                   # python-3.12 (Streamlit Cloud pin)
│
├── 🔐 .streamlit/
│   └── secrets.toml                 # GROQ_API_KEY (gitignored)
│
├── ⚙️ config/
│   └── categories.json              # 12 categories · 300+ keywords · icons · hex colors
│
├── 🗃️ data/
│   └── sample_transactions.csv      # 90 demo transactions across 3 months
│
└── 🐍 modules/
    ├── __init__.py
    ├── parser.py                    # CSV ingestion, 11 date formats, 4 UPI formats
    ├── categorizer.py               # Keyword reverse-index categorizer
    ├── anomaly_detector.py          # 6-method anomaly detection engine
    ├── insights.py                  # Behavioral patterns, nudges, subscriptions
    ├── charts.py                    # 8 Plotly chart builders (dark theme)
    ├── budget_tracker.py            # Monthly goals + burn-rate projection
    ├── forecaster.py                # Auto-ARIMA / Holt-Winters ETS / Linear
    ├── deduplicator.py              # Fuzzy multi-account deduplication
    ├── ai_advisor.py                # Groq chat advisor (Llama 3.3 70B)
    └── benchmarks.py               # India city-tier peer comparison engine
```

<br/>

## 📤 Supported CSV Formats

<div align="center">

| UPI App | How to Export |
|---------|--------------|
| **Google Pay** | GPay app → Profile → Statement → Download CSV |
| **PhonePe** | PhonePe → History → Download Statement → Email CSV |
| **Paytm** | Paytm → Passbook → Download Statement |
| **BHIM** | Transaction History → Export |
| **Any Bank** | Any CSV with `Date`, `Description`, `Amount` columns |

**Minimum required columns:** `Date` · `Description` · `Amount`

</div>

<br/>

## 🔒 Privacy First

```
Your Data Never Leaves Your Machine
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  CSV Upload ──→ Local Processing ──→ Local Dashboard
                        │
                        ▼
              ONLY the 🤖 AI Advisor page
              sends a STATISTICAL SUMMARY
              (category totals, averages, counts)
              to Groq API

              ❌ Raw transaction descriptions
              ❌ Merchant names
              ❌ Exact amounts
              → are NEVER sent anywhere

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

<br/>

## ⚙️ Configuration & Tuning

**Add or modify spending categories** in `config/categories.json`:
```json
"My Category": {
  "keywords": ["merchant name", "keyword", "upi@handle"],
  "icon": "🏷️",
  "color": "#FF6B6B"
}
```

**Tune anomaly sensitivity** in `modules/anomaly_detector.py`:
```python
Z_SCORE_THRESHOLD     = 2.5   # Lower = more anomalies flagged
IQR_MULTIPLIER        = 2.0   # Lower = stricter per-category outlier detection
LARGE_ROUND_THRESHOLD = 5000  # Minimum ₹ for round-number flag to trigger
```

**Tune deduplication strictness** in `modules/deduplicator.py`:
```python
FUZZY_THRESHOLD  = 72   # 0–100, lower catches more (riskier) duplicates
DATE_WINDOW_DAYS = 1    # ±N days window for same transaction
AMOUNT_TOLERANCE = 1.0  # ₹ difference allowed for amount match
```

<br/>

## 🗺️ Roadmap

- [ ] 📸 WhatsApp/screenshot OCR parser using Tesseract
- [ ] 📄 PDF tax summary — 80C investment auto-detection
- [ ] 🔁 UPI ID network graph (NetworkX + Pyvis)
- [ ] 📱 Progressive Web App (PWA) mobile mode
- [ ] 🔔 Budget breach WhatsApp / email alerts
- [ ] 🏦 Live bank sync via Setu / Finbox AA APIs
- [ ] 🌍 Multi-currency support for NRI users

<br/>

## 🤝 Contributing

Contributions are very welcome!

1. Fork the repository
2. Create your feature branch — `git checkout -b feature/AmazingFeature`
3. Commit your changes — `git commit -m 'Add AmazingFeature'`
4. Push to the branch — `git push origin feature/AmazingFeature`
5. Open a Pull Request

<br/>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=100&section=footer" width="100%"/>

<br/>

**Built with ❤️ for India's 500M+ UPI users**

<br/>

[![Live Demo](https://img.shields.io/badge/🚀%20Try%20It%20Now-fintrack--ai--upi--spend--analyzer.streamlit.app-6C63FF?style=for-the-badge)](https://fintrack-ai-upi-spend-analyzer.streamlit.app/)

<br/>

*If this project helped you, please give it a ⭐ — it means a lot!*

</div>
