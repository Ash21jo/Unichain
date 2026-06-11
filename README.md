# Unichain
UniChain is a consortium blockchain solution designed to eliminate the high costs and delays of cross-border tuition payments for international students. Built on the Polygon Amoy Testnet, UniChain issues a USD-pegged ERC-20 stablecoin — UniCoin (UNI) — that enables near-instant, low-cost tuition settlement between students and universities worldwide.

The problem it solves: International students currently pay 8–12% in fees and wait 3–5 business days for cross-border wire transfers. UniChain brings that down to a $0.50 flat fee and ~3-second settlement.
🎓 Student Node          ⛓️ UniChain             🏛️ University Node
  MetaMask Wallet    →   ERC-20 UniCoin      →   Multi-sig Treasury
  Polygon Amoy           Polygon Amoy Testnet     Rennes SB

                  🏦 Partner Bank — KYC/AML + Fiat On/Off Ramp
                  UniCoin (UNI) — 1 UNI = 1 USD stablecoin peg
Total Supply — 1,000,000 UNI
Regulation — Fiat on/off ramp handled by licensed banks (KYC/AML compliant); blockchain handles settlement only
 <img width="1470" height="956" alt="Screenshot 2026-03-10 at 5 40 55 PM 8 51 33 AM" src="https://github.com/user-attachments/assets/e69887b0-28b0-475f-ad73-e7acd3527cf2" />
 NameUniCoinSymbolUNIStandardERC-20Peg1 UNI = 1 USDTotal Supply1,000,000 UNIDecimals18NetworkPolygon Amoy TestnetPer Member (6 members)~166,667 UNI
 <img width="1470" height="956" alt="Screenshot 2026-03-23 at 8 59 21 AM" src="https://github.com/user-attachments/assets/0024a853-67b4-4c8c-bc65-1a3a601f306e" />
<img width="1470" height="956" alt="Screenshot 2026-03-23 at 8 56 50 AM" src="https://github.com/user-attachments/assets/a6ff9921-f9f3-42ce-a801-0c6fdb8906a7" />
Step-by-Step

1. Install MetaMask

Browser extension → Create wallet → Secure your seed phrase

2. Add Polygon Amoy Testnet

RPC URL  : https://rpc-amoy.polygon.technology
Chain ID : 80002
Symbol   : POL


⚠️ Use Polygon Amoy (not Mumbai) — the updated testnet as of 2024. The currency symbol is POL, not MATIC.



3. Fund with Test POL


Select: Amoy Testnet
Receive: 0.5–2 POL

4. Connect to thirdweb

thirdweb.com → Connect Wallet → Select MetaMask → Verify Amoy network

5. Verify all team wallets

All 6 members repeat steps 1–4 and share wallet addresses with the team


🚀 Token Deployment

The UniCoin ERC-20 contract was deployed via thirdweb:

1. thirdweb.com → Deploy Contract → Token (ERC-20)
2. Name: UniCoin | Symbol: UNI | Supply: 1,000,000
3. Network: Polygon Amoy Testnet
4. Click Deploy → Confirm in MetaMask (~0.001 POL gas)
5. Contract address: 0x48046a8166f628329e1EE9Fa096e44fB6D105749



