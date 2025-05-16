# axiom-strat
# Axiom Trading Strategies for Solana

This repository contains JSON-based filter and strategy configs for [Axiom](https://axiom.trade), optimized for safely trading new token pairs on Solana.

## Contents

- `configs/solana_safe_filter.json` – Conservative filter for new Solana pairs
- `configs/solana_new_pair_strategy.json` – Auto-buy strategy using the safe filter

## How to Use

1. Copy the config files into your Axiom instance's folder
2. Load them via the GUI or CLI
3. Enable paper trading to test strategies safely
4. Customize parameters like buy size, SL/TP, and cooldowns as needed

> Always test in paper mode before going live with real funds.
