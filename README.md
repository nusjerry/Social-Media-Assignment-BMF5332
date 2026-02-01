# Social Media Assignment: Foundations of Investment (BMF5332)

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

#AssetAllocation #QuantFinance #Investing #Python #PortfolioManagement
<img width="1790" height="390" alt="image" src="https://github.com/user-attachments/assets/04d50d68-ab1e-4e4a-ac7b-6e1e959f92f7" />
<img width="1611" height="611" alt="image" src="https://github.com/user-attachments/assets/d7842113-2683-4759-8e21-dc719efdb5f1" />
<img width="1389" height="689" alt="image" src="https://github.com/user-attachments/assets/31d44360-3124-494c-8dbb-9f3c6f92d47c" />
<img width="1810" height="611" alt="image" src="https://github.com/user-attachments/assets/b0c4321a-d898-4522-83cd-6a32ea9b3eef" />




