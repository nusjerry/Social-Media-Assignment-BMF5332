# Social-Media-Assignment---Foundations-of-Investment

🚨 Portfolio Reality Check: 60/40 vs. The Efficient Frontier

I rebuilt a Markowitz mean–variance pipeline in Python to test whether the classic 60/40 allocation holds up against an optimized tangency portfolio.

📊 Inputs (sample):
• Stocks: S&P 500 Total Return (Yahoo)
• Bonds: 7–10Y Treasuries (IEF)
• Risk-free: 3‑month T‑Bills (FRED)
• Global: JST equal‑weighted 18‑country index (annual → monthly approximation)

1️⃣ 60/40 benchmark:
• Ann. Return: 22.91%    • Volatility: 16.17%
• Sharpe: 1.42

2️⃣ 'Optimal' (Tangency) portfolio:
• Weights (Stocks/Bonds): 30.5% / 69.5%
• Sharpe: 1.44

⚠️ Key caveat:
Naive Markowitz is sensitive to estimation error: small changes in means/covariances can produce large swings in optimized weights. Treat tangency weights as a theoretical benchmark, not a mechanical allocation rule.

Verdict: 60/40 remains a practical behavioral baseline; optimization highlights tradeoffs but can be unstable without robust estimation or constraints.

See attached exhibits (Efficient Frontier, Correlation Matrix, Drawdowns). Confirm these numbers against the notebook if you rerun the analysis.

#AssetAllocation #QuantFinance #Investing #Python #PortfolioManagement
