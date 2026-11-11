# OOBE Protocol — Steve Capital Autonomous Capital Agent Submission (`500 USDC`: Main + MultiHopper + Ace Data Cloud)

- **Bounty Listing**: [Build an Autonomous Capital Agent on Solana & Compete for $500 in Rewards](https://earn.superteam.fun/listings/bounty/build-an-autonomous-capital-agent-on-solana-and-compete-for-dollar500-in-rewards) (`591423c3-bb3e-4f91-8ff0-69f163038ede`)
- **Agent Wallet Address**: `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt` ([Solscan Explorer](https://solscan.io/account/Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt))
- **EVM Companion Address**: `0x971b573b47357c22a67FcE8c56Aaeb478356C942`

---

## 1. Eligibility Question Response
- **Question**: *"Share your agent wallet adress + any transaction link on Solana explorer / solscan if relevant."*
- **Answer**: `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt` — Solscan Explorer: https://solscan.io/account/Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt

---

## 2. Main Track Architecture (`250 USDC`): Programmable Guardrails & Specialist Sub-Agents
Our autonomous capital agent (`oobe_capital_agent.py`) is built for **Steve Capital (`https://steve.oobeprotocol.ai`)** and **SAP MCP**, enforcing strict risk mandates:
- **Guardrails**: `50 bps` max slippage, `15%` max single-swap NAV exposure, `1.25` minimum Kamino lending health factor, `3.5%` daily drawdown circuit breaker, and strict anti-wash-trading / anti-circular-routing verification.
- **4 Delegated Sub-Agents**:
  1. `YieldGuardSubAgent` (`45%` allocation): Tracks real-time lending & CLMM yields across **Kamino** (`KLend2g3cP87fffoy8q1mQqGKjrxjC8boSyAYavgmjD`), **Raydium CLMM** (`CAMMCzo5YL8w4VFF8KVHrK22GGUsp5VTaW7grrKgrWqK`), **Orca Whirlpool** (`whirLbMiicVdio4qvUfM5KAg6Ct8VwpYzGff3uctyCc`), and **Meteora DLMM** (`LBUZKhRxPF3XUpBCjp4YzTKgLccjZhTSDM9YuVaPwxo`).
  2. `SpotPerpsExecutionSubAgent` (`30%` allocation): Executes spot rebalances via **Jupiter V6** (`JUP6LkbZbjS1jKKwapdHNy74zcZ3tLUZoi5QNyVTaV4`) and macro commodity hedges (synthetic Gold `XAU` / Silver `XAG`) via **Adrena**.
  3. `MultiHopperRoutingSubAgent` (`15%` allocation): Automates non-custodial treasury distributions across sub-agent vaults using **MultiHopper MCP**.
  4. `AceDataCloudIntelSubAgent` (`10%` allocation): Runs pre-trade research, sentiment analysis, chart generation, and voice briefings via **Ace Data Cloud MCP**.

---

## 3. Partner Side-Track 1: MultiHopper x Steve Capital (`125 USDC`)
- **Verified On-Chain MultiHopper Programs**:
  - **MultiHopper Core**: `3jLoS2wbNgtKzieUUxwg6Xhdv6gbZkHDtPWA9ZAgspFh` (Verified Executable on Solana Mainnet)
  - **MultiHopper Orchestrator**: `4TPCmR2uN3hDM1FbTsf7ZtFXwXGSz4u1Kxv5YHj6eruX` (Verified Executable on Solana Mainnet)
  - **Token2022 Transfer Hook Guard**: `2JEv3pD6nczEvn1xDXaEzehkJofPPjoQQpnW5nGY3r52` (Verified Executable on Solana Mainnet)
- **Public Social Post (`@Multihopper @OOBEonSol @SteveCapitalOS`)**:
  > Built a non-custodial Sub-Agent Treasury Distribution workflow on **@SteveCapitalOS** powered by **@OOBEonSol** & **@Multihopper** (`3jLoS2wbNgtKzieUUxwg6Xhdv6gbZkHDtPWA9ZAgspFh`)! Harvested Kamino/Raydium yields are TRM-screened and routed across 3 specialist sub-agent vaults via Token2022 wrapper hooks. Wallet: `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt`

---

## 4. Partner Side-Track 2: Ace Data Cloud x Steve Capital (`$125 Total Value`)
- **5 Qualifying Paid Service Requests Workflow (`ace_data_cloud_intel_agent`)**:
  1. `ace.google_search`: Real-time Solana Kamino USDC supply APY vs Raydium SOL-USDC CLMM 24h fee APR comparison.
  2. `ace.google_search`: FOMC rate probability & XAU spot macro volatility filter for Adrena synthetic gold perpetual hedging.
  3. `ace.research_agent`: Pre-trade liquidity depth & holder concentration audit for Meteora DLMM pools.
  4. `ace.image_generation`: Daily portfolio PnL & risk allocation infographic for Steve Capital Agent Space.
  5. `ace.voice_narration`: 60-second narrated executive audio briefing summarizing daily Arena XP and MultiHopper treasury routes.
- **Public Social Post (`@acedatacloud @OOBEonSol @SteveCapitalOS`)**:
  > Connected our **@SteveCapitalOS** autonomous capital agent (**@OOBEonSol**) to **@acedatacloud** MCP! Before reallocating capital across Kamino, Raydium & Adrena XAU perps, our intel sub-agent runs 5 Ace MCP calls (search, liquidity audit, chart gen & voice briefing). Wallet: `Aw2hhJvjewAcxssyWMzKmFge6jWxEzN6GiFQgyZNKakt`
