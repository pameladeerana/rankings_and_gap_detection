# Ethereum Gas Rankings and Nonce Gap Detection

## Description
Analysis to rank top gas spenders an detect nonce gaps on a 7-day dataset (Nov 2 - Nov 8, 2026 PHT). This analysis has two parts. The first part shows who drives the network each day. Knowing the big movers is important because it helps spot possible spikes in activity, like when a big player, exchange, or bot suddenly dominates. The second part shows where transactions (nonces) went missing. It's about catching a broken payout or a stuck system early, fixing the missing number, and keeping the transactions flowing.

## 1. Parts / Statements

**1. Daily Top Gas Spender**
Rank wallets by total gas paid per day. Shows who paid the most gas in ETH and Gwei.

**2. Nonce Gap Detection**
Detect missing nonce per wallet. A gap happens when a wallet's nonce jumps from a number to another. 

## 2. Workflow

1. Explored tables on Dune, picked the block range for last 7 days (Nov 2 - Nov 8, 2026).
2. Queried dataset for 2 parts (assisted with WizardsCamp and AI for automation of queries).
3. Made visualizations and built final dashboard.

## 3. Files

- **README.md** - Project overview.
- **Dune Queries and Results**:
  - Data Source: https://dune.com/queries/9110148?sidebar=none
  - Part 1 - Daily Top Gas Spender: https://dune.com/queries/9110292
  - Part 2 - Nonce Gap Detection: https://dune.com/queries/9110861
- **Dune Dashboard**: https://dune.com/pameladeerana/rankings-and-gap-detection

## 4. Data Coverage

- **Date:** November 2 - November 8, 2026 PHT
- **Blocktime Range:** 2026-11-01 16:00:00 to 2026-11-08 16:00:00 UTC (from query_9110148) 

## 5. Tools

- Dune Analytics
- WizardCamp
- LLM Meta AI

## Author

Pamela Dee Elegio Rana
