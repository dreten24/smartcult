# Smart SOL (sSOL) — Fixed Supply (1B) on PoW EVM

- Max supply: **1,000,000,000** sSOL (hard cap enforced in contract)
- Mint authority: **TREASURY only**, cannot exceed cap
- Included: `VestingVault.sol` (linear vesting) and `MerkleAirdrop.sol` (one-time airdrop)

## Quickstart
1. Install Node 18+, `npm i` then `npx hardhat compile`.
2. Configure a PoW EVM RPC (Smart DOGE chain etc.) in `hardhat.config.ts` (add networks).
3. `npx hardhat run scripts/deploy.ts --network <yourNetwork>`
4. Record addresses for token and vault.

> This project is chain-agnostic and intended for PoW EVM deployments (e.g., Smart DOGE EVM).