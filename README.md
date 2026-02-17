# $Efe Nexus Pi Contract

Fixed-ratio token on the Pi Network blockchain.  
**1 $EFE = exactly 3.14159 PI** (π-inspired peg)

### How it works
- Deposit PI → mint $EFE at the fixed ratio  
- Burn $EFE → redeem exact PI back (minus network fees)  
Pure on-chain enforcement. No fiat, no oracles.

"Stable" only relative to PI's price — perfect for Pi ecosystem tools, micro-payments, or π-themed apps.

### Status
Early Testnet prototype.  
Not audited — use at your own risk.  
Mainnet deployment planned after Pi DEX launch (\~March 2026).

### Tech
- Rust + Soroban SDK (WASM)  
- Pi Network smart contracts  
- Tools: soroban-cli, Cargo, Rustup

### Quick Start (Local / Testnet)
1. `rustup target add wasm32-unknown-unknown`  
2. `cargo install soroban-cli` (or Pi's version if different)  
3. Build: `cargo build --target wasm32-unknown-unknown --release`  
4. Deploy to Pi Testnet (fund wallet via faucet first)

Full deployment guide coming once Pi docs finalize RPC/CLI details.

### Risks
- PI volatility = $EFE volatility (not fiat-stable)  
- Smart contract bugs = potential loss of funds  
- Experimental — follow Pi Network rules (KYC, etc.)

Contributions welcome: fork, PR, issues.  
Let's build something cool on Pi.

Questions? DM me → @EfeNexus on X

License: MIT
