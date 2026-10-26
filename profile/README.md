<p align="center"><img src="https://raw.githubusercontent.com/Lockdfun/.github/main/assets/lockd-banner.png" alt="lockd: memecoin launches with rules that can't be broken" width="100%"></p>

<p align="center">
  <a href="https://lockd.trade">App</a> ·
  <a href="https://lockd.trade/docs">Docs</a> ·
  <a href="https://x.com/Lockdlabs">X</a>
</p>

---

Lockd is a launchpad on Solana. Each coin's rules are written on chain at launch and enforced on every transfer, so nobody has to trust the dev.

**What a creator can set**

- **Early-buyer lock**: part of every early buy stays locked until a date, a traded volume or graduation.
- **Max wallet** and **creator lock**, enforced by a Token-2022 transfer hook.
- **Holder rewards**, paid in SOL from trading fees with no custody: no wallet of ours ever holds them.
- **Anti-sniper fee** and **creator fee**, through Meteora.

**How it runs**

Coins launch on [Meteora's Dynamic Bonding Curve](https://www.meteora.ag/) and graduate at 10× their opening market cap to a DAMM v2 pool with liquidity locked for good. Fees flow into a per-coin vault no key controls; any wallet can trigger the payouts.

**For traders**

Every coin page shows an exit simulator, a graduation preview and a launch score whose points all come from rules or on-chain reads.

**Trust**

The hook was audited externally before mainnet and every finding fixed. Its upgrade authority is a Squads multisig (2 of 3), the platform's fee address is fixed in the program, and the launch lookup table is frozen.

| | Mainnet |
|---|---|
| Lock hook | [`LockoiXyf2fY5QGerQdoZxoThg3kyboG97cyiy12FDk`](https://explorer.solana.com/address/LockoiXyf2fY5QGerQdoZxoThg3kyboG97cyiy12FDk) |
| Platform treasury (Squads vault) | [`FNVEukNM1MLoEEJMAEtSCePrKbba15crrCfaW2U91d6i`](https://explorer.solana.com/address/FNVEukNM1MLoEEJMAEtSCePrKbba15crrCfaW2U91d6i) |

---

<p align="center"><sub>Live on Solana mainnet. Buyback &amp; burn and creator vesting are coming next.</sub></p>
