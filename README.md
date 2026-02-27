# Ronin Bridge Validator Key Compromise — PoC

> **Educational Purpose Only** — This PoC is created for security research and education
> purposes only. It runs against a fork, not mainnet.

## Quick Start

```bash
git clone https://github.com/NomosLabs-Security/poc-ronin-bridge-2022
cd poc-ronin-bridge-2022
forge test -vvvv
```

## Details

- **Exploit Date:** 2022-03-23
- **Fork Block:** #14442840
- **Expected Output:** 5/9 multisig threshold bypass simulation
- **Full Analysis:** [NomosLabs Security Intelligence Archive](https://nomoslabs.io/archive/ronin-bridge-2022)

## Description

The Ronin Bridge exploit was not a smart contract bug but a validator key compromise.
This PoC simulates the bridge contract's multisig mechanism and demonstrates how the
5/9 threshold was bypassed.

This PoC demonstrates:
1. Simplified bridge withdrawal + multisig validation
2. Valid withdrawal approval with 5/9 threshold
3. The risk of a single organization controlling 5+ keys

## RPC Providers

```
Alchemy:   https://eth-mainnet.alchemyapi.io/v2/YOUR_KEY
Infura:    https://mainnet.infura.io/v3/YOUR_KEY
QuickNode: https://YOUR_ENDPOINT.quiknode.pro/YOUR_KEY
```

## License

MIT — For educational use only.
