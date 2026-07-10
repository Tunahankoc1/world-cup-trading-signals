# World Cup Trading Signals

AI-powered trading signals based on live World Cup 2026 odds and match results, recorded on-chain via Solana.

🌐 **Live Demo:** [world-cup-trading-signals.vercel.app](https://world-cup-trading-signals.vercel.app)

---

## What It Does

### 1. Fetches Live Data
- **TxLINE API** — real-time match odds
- **WorldCup26 API** — live match results and scores

### 2. Generates Trading Signals
| Condition | Signal |
|-----------|--------|
| Favorite lost | 🔴 SELL |
| Underdog won | 🟢 BUY |
| Odds decreasing | 🟢 BUY |
| Odds increasing | 🔴 SELL |
| No change | 🟡 HOLD |

### 3. Displays
- Confidence score (%)
- AI-generated explanation for each signal
- WIN / LOSS badge per match
- Live match score

### 4. Records On-Chain
- "Record Signal On-Chain" button
- Sends a **Memo transaction** to Solana — signal permanently stored on blockchain

---

## Tech Stack

- **Frontend:** HTML + JavaScript (single file, no build step)
- **Blockchain:** Solana (Memo program)
- **APIs:** TxLINE (odds), WorldCup26 (results)
- **Deployment:** Vercel

---

## How to Run

```bash
# Clone the repo
git clone https://github.com/Tunahankoc1/world-cup-trading-signals
cd world-cup-trading-signals

# Open in browser
open index.html
# or just visit the live demo
```

---

## Built For

[Superteam World Cup Hackathon](https://superteam.fun/earn/hackathon/world-cup) — Markets Track
