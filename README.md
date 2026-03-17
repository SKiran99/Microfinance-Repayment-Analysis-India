# Microfinance-Repayment-Analysis-India
Analysis of loan repayment patterns, default rates, and PAR across 80,000 MFI loans in India using PLFS and MFIN data.


# 💳 Microfinance Loan Repayment Patterns in India

> **A large-scale data analysis of borrower behavior, default risk, and portfolio health
> across 80,000 simulated MFI loan records — grounded in MFIN Micrometer and
> MIX Market microfinance data structures.**

---

## 📌 Project Overview

Microfinance institutions (MFIs) serve over 60 million low-income borrowers in India,
providing credit access to populations excluded from formal banking. Yet repayment
behavior varies sharply across states, loan types, borrower demographics, and loan
cycles — creating significant portfolio risk for MFIs and policy challenges for regulators.

This project builds and analyzes a large microfinance loan-level dataset to uncover
patterns in repayment rates, Portfolio at Risk (PAR), and the drivers of loan default.

---

## 🔬 Research Questions

1. Which Indian states exhibit the highest loan default rates and PAR30?
2. Does loan cycle number, loan size, or group lending model affect repayment?
3. How do gender and rural/urban location relate to repayment behavior?
4. What is the PAR distribution across MFI loan portfolios, and where is stress concentrated?

---

## 📊 Key Findings

| Finding | Result |
|---|---|
| Overall Portfolio Default Rate | ~10–12% (varies by state) |
| Highest Default State | Andhra Pradesh / Telangana |
| Gender Repayment Gap | Women default ~5 pp less than men |
| Loan Cycle Effect | Default rate falls with each repeat cycle |
| PAR30+ Portfolio Share | ~8–10% of loan value |
| Riskiest Loan Purpose | Health Emergency loans |

---


# 📂 Data Sources — Microfinance Repayment Analysis

## Primary Reference Sources

### 1. MFIN Micrometer
- **Provider:** Microfinance Institutions Network (MFIN)
- **URL:** https://mfinindia.org/resources/micrometer
- **Contains:** Quarterly portfolio data, PAR metrics, state-wise MFI stats
- **Access:** Free (PDF reports)

### 2. MIX Market
- **Provider:** CGAP / World Bank Group
- **URL:** https://www.themixmarket.org
- **Contains:** MFI-level financial and operational data across countries
- **Access:** Free registration required

### 3. Sa-Dhan Bharat Microfinance Report
- **Provider:** Sa-Dhan (Industry Association)
- **URL:** https://www.sa-dhan.net
- **Contains:** Annual MFI performance benchmarks, state coverage data
- **Access:** Free

### 4. RBI Financial Inclusion Data
- **Provider:** Reserve Bank of India
- **URL:** https://www.rbi.org.in/Scripts/AnnualReportPublications.aspx
- **Contains:** NBFC-MFI regulation data, priority sector lending stats
- **Access:** Free

## Dataset Note
This project uses a simulated dataset whose structure and distributions
are grounded in the above sources. Variable definitions follow MFIN
Micrometer reporting standards.


## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3.10+ | Core language |
| Pandas | Data manipulation & merging |
| NumPy | Numerical computation |
| Matplotlib | Static visualizations |
| Seaborn | Statistical plots |
| SciPy | Statistical tests |

---


## 📄 License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
