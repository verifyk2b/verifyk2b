# Verify K2B

On-chain facts for K2B (Krumbs 2 Bricks) on Solana.

Live pages:
- Site: https://krumbs2bricks.com/
- Verify: https://krumbs2bricks.com/verify/

If this README and Solscan do not match, Solscan wins.

## Core facts

- Token: K2B
- Chain: Solana
- Original supply: 1,000,000,000
- Mint supply now: 958,907,518.51
- Mint authority: revoked
- Freeze authority: revoked

## Mint / buy address

`At4L287tND4vLSURFeVz2fqhbvNgnE76nfFg7gy9pump`

- [Solscan (mint)](https://solscan.io/token/At4L287tND4vLSURFeVz2fqhbvNgnE76nfFg7gy9pump)
- [Pump.fun](https://pump.fun/At4L287tND4vLSURFeVz2fqhbvNgnE76nfFg7gy9pump)

## Burns

Incinerator token account (K2B ATA):

`C9TePxZ41j2yDkDGgLxLT1ztLdvMpgpVNDSRv9cmq1K3`

This is the associated token account owned by Solana’s incinerator
(`1nc1nerator11111111111111111111111111111111`).
No private key. Tokens here cannot be moved.

Balance: 169,821,597.91 K2B

- [Incinerator ATA](https://solscan.io/account/C9TePxZ41j2yDkDGgLxLT1ztLdvMpgpVNDSRv9cmq1K3)
- [Incinerator](https://solscan.io/account/1nc1nerator11111111111111111111111111111111)

Sending tokens to the incinerator does not lower Solscan’s mint supply.
That is why mint supply still shows 958,907,518.51.
About 41,092,481.49 was separately burned at the mint.
Combined, about 210.9M K2B is out of circulation.

## Token locks (Streamflow)

These are the current metadata accounts after the Feb 2026 migration.
Old IDs `5P7k` / `DhPS` / `6tLv` were closed.

- 100,000,000 K2B · unlock 2031-01-04 (\~5y)  
  `HRuWdSV9npJt5Kd16pGgQWA9cD5ZfEEnez9dpGx86QaJ`  
  [View 5y lock](https://app.streamflow.finance/contract/solana/mainnet/HRuWdSV9npJt5Kd16pGgQWA9cD5ZfEEnez9dpGx86QaJ)

- 100,000,000 K2B · unlock 2036-01-04 (\~10y)  
  `ARCTKw6W5msQzYRCgMkMsff7uYLxEkzzCqU8dr5fDFH1`  
  [View 10y lock](https://app.streamflow.finance/contract/solana/mainnet/ARCTKw6W5msQzYRCgMkMsff7uYLxEkzzCqU8dr5fDFH1)

- Raydium CLMM position NFT · unlock 2041-01-04 (\~15y)  
  `2f4K6vcK14rHFn2tAJwK8pPJaWDF8Vhkse7umC4pLiU1`  
  This is a Raydium concentrated-liquidity position NFT. It is not the Orca pool.  
  [View 15y LP lock](https://app.streamflow.finance/contract/solana/mainnet/2f4K6vcK14rHFn2tAJwK8pPJaWDF8Vhkse7umC4pLiU1)

## Liquidity pools

Separate venues. Amounts change. Check the links.

- PumpSwap (main trading pool): `H733HRgPCTeZbTKyLmbsf986czovQMoHtTQxwMSU1QTb`  
  [Solscan](https://solscan.io/account/H733HRgPCTeZbTKyLmbsf986czovQMoHtTQxwMSU1QTb) · [Dexscreener](https://dexscreener.com/solana/h733hrgpctezbtkylmbsf986czovqmohttqxwmsu1qtb)

- Orca Whirlpool (WSOL-K2B): `4YXiuFu5qWDeUqKAMGFbSAM1eimADvjsS3HW2k7EqYnh`  
  [Solscan](https://solscan.io/account/4YXiuFu5qWDeUqKAMGFbSAM1eimADvjsS3HW2k7EqYnh)

- Meteora: `E4gvAs2mjkdNk1fVqFVNnDp6AM36LQydaQCxr4v2ASRh`  
  [Solscan](https://solscan.io/account/E4gvAs2mjkdNk1fVqFVNnDp6AM36LQydaQCxr4v2ASRh)

- Raydium CLMM (Jan 5, 2026 — locked position pool): `Ds7HDw7Q9AZuQ9cyNTaSHhdVG1Sjw8pFgCDnJANGRE4n`  
  [Solscan](https://solscan.io/account/Ds7HDw7Q9AZuQ9cyNTaSHhdVG1Sjw8pFgCDnJANGRE4n)

- Original pump.fun bonding curve (historical): `sPJ7Ae8Z77xNR281gdFjfCScAN6RWCb3GinsvZ2v39g`  
  [Solscan](https://solscan.io/account/sPJ7Ae8Z77xNR281gdFjfCScAN6RWCb3GinsvZ2v39g)

Additional smaller Raydium CLMM and Meteora DAMM v2 pools exist. They are separate from the locks above.

## Scope

On-chain facts only. No guarantees. No projections.
