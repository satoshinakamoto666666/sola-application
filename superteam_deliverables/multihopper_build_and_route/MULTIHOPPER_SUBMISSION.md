# MultiHopper Build & Route Challenge Submission (`5,000 USDC` Guaranteed Base Pool — Up to `$50,000 USDC` + `0.25%` Revenue Share)

- **Bounty Listing**: [MultiHopper Build & Route Challenge | Up to $50,000 + Revenue Share](https://earn.superteam.fun/listings/bounty/multihopper-build-and-route-challenge-up-to-dollar50000-revenue-share-1) (`6506004c-0442-4233-8af1-cf5e26919d71`)
- **Solana Payout & Integrator Wallet**: `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt` ([Solscan](https://solscan.io/account/Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt))

---

## 1. User Problem & MultiHopper Integration Architecture
Autonomous AI agent swarms on Solana manage treasury vaults, pay x402 API providers (`Swap.io`), fund specialist sub-agents (`Steve Capital`), and distribute contributor payouts. Direct single-hop transfers expose treasury vault linkability and lack programmable settlement timing or built-in compliance screening.

Our **MultiHopper Programmable AI Agent Treasury & Multi-Send Engine (`multihopper_treasury_router.py`)** integrates MultiHopper's 3-call REST flow (`/api/v1/transfers`, `/api/v1/transfers/:id/prepare`, `/api/v1/transfers/:id/confirm-broadcast`) and on-chain Anchor smart contracts:
- **MultiHopper Core (`3jLoS2wbNgtKzieUUxwg6Xhdv6gbZkHDtPWA9ZAgspFh`)**: Verified executable on Solana Mainnet-Beta.
- **Orchestrator (`4TPCmR2uN3hDM1FbTsf7ZtFXwXGSz4u1Kxv5YHj6eruX`)**: Verified executable on Solana Mainnet-Beta.
- **Transfer Hook Guard (`2JEv3pD6nczEvn1xDXaEzehkJofPPjoQQpnW5nGY3r52`)**: Verified executable on Solana Mainnet-Beta (enforces Token2022 permanent delegate & TRM Labs smart-contract screening).

---

## 2. Qualifying Volume & 0.25% Atomic Integrator Revenue Model
- **50/50 Fee Split**: Customers pay `0.50%` on full-rate transfers; `0.25%` (`$2,500 USDC` per `$1M` routed) is paid atomically on-chain to our integrator wallet `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt`.
- **Anti-Abuse Enforcement**: `multihopper_treasury_router.py` strictly blocks circular/self-transfers (`d["wallet"] != source_wallet`), counts principal once across up to 20 Multi-Send recipients, and verifies HMAC-SHA256 webhook callbacks.
