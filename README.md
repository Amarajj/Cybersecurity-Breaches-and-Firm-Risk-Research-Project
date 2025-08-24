# Cybersecurity-Breaches-and-Firm-Risk-Research-Project
This project investigates the impact of data breach announcements on firm risk in U.S. publicly traded companies. 
Using a matched dataset of breach events (sourced from the Privacy Rights Clearinghouse and other disclosure databases) and firm-level financials (Compustat, CRSP), the study measures how breaches affect total risk, systematic risk, and idiosyncratic risk.
The analysis is grounded in Signaling Theory and the Real Options Perspective, proposing that breaches act as negative signals of managerial oversight while simultaneously reshaping firms’ strategic and risk-return profiles.


Objectives

Examine whether total stock return volatility (TVOL) increases after breach announcements.
Test if breaches affect firms’ systematic risk (beta) relative to the market.
Measure changes in idiosyncratic volatility (IVOL) as a proxy for firm-specific uncertainty.
Identify firm characteristics (size, profitability, leverage, growth opportunities, industry) that influence risk outcomes.
Estimate cross-sectional OLS regressions with and without fixed effects to uncover significant predictors.


Data & Methodology
Data Sources:
Privacy Rights Clearinghouse (Data Breach Chronology)
Compustat (financials, firm characteristics)
CRSP (daily returns, market beta estimation)
Sample: ~3,800 firm-breach observations (2011–2024).
Risk Measures:
TVOL – standard deviation of daily returns.
Beta – market sensitivity via CAPM regression.
IVOL – standard deviation of residuals from CAPM regression.


Analysis

Event study design (pre vs. post announcement windows).
Summary statistics, correlation, and distribution tables.

Panel regressions:
ΔRisk = f(high_tech, leverage, ROA, FCF, M/B, PPE, size, liquidity, industry FE, year FE).
Key Findings (so far)
Total volatility (TVOL) generally increases post-breach (supporting H1).
Beta shows modest but mixed changes (partially supporting H2).
Idiosyncratic volatility (IVOL) rises significantly, consistent with breach-specific uncertainty (supporting H3).
Firm fundamentals (ROA, leverage, growth opportunities) significantly shape the magnitude of risk change.

