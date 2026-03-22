---
description: All smart contracts deployed by the Curve Bonds DAO Protocol
---

# Contracts & Token Addresses

#### Overview

This page provides a complete list of Curve Bonds DAO token contracts and core protocol contracts.\
All addresses are deployed on Ethereum unless otherwise specified.

Users are encouraged to independently verify all contracts on-chain.

***

### Native Tokens

#### USD Stablecoins

| Token | Description                         | Contract Address                             |
| ----- | ----------------------------------- | -------------------------------------------- |
| CBD   | Base stablecoin (non-yield-bearing) | `0x7d9a9bC5646C8B2B89Dc72E2fe98b2CE8d737381` |
| sCBD  | Yield-bearing stablecoin            | `0xb7d569d63f92E3C0454984B7Da4426e83d453E7A` |

#### ETH Derivative Stack

| Token   | Description                  | Contract Address                             |
| ------- | ---------------------------- | -------------------------------------------- |
| cbdETH  | Base ETH token               | `0xe5736Fd5ea3412b62CaA20c6547d2b8f8E61D363` |
| scbdETH | Yield-bearing ETH derivative | `0xF46E0a7799D73897C978b6EFe4Bb44795EBdabd8` |

#### Bond Tokens

| Token          | Description                 | Contract Address                             |
| -------------- | --------------------------- | -------------------------------------------- |
| BOND           | Core DAO / bond token       | `0x0204F05Af77c640eF80675dEC46fF90CF996A90A` |
| sBOND          | Staked BOND (yield-bearing) | `0xBC03f8d07D2DCdA3f846938F64898EB4769d2806` |
| vBOND          | Vote Locked BOND token      | `0x7ae4a4C32E4923D05cE641E3DF6a98d73a10A7ac` |
| VestedBOND2026 | Vested BOND Reward Token    | `0x737d17A3D348f80a0FDd9730873f586952139082` |

***

### Staking Contracts

| Contract              | Description                          | Address                                      |
| --------------------- | ------------------------------------ | -------------------------------------------- |
| sCBD Staking Rewards  | Stake sCBD to earn protocol rewards  | `0xeA49b04D6202d09247b1e924291bdb467e9EDD7a` |
| vBOND Staking Rewards | Stake vBOND to earn protocol rewards | `0xd7714d78b97e1d74b95ca672cea7fa76b9bb6377` |

***

### Conversion Contracts

| Contract                | Description               | Address                                      |
| ----------------------- | ------------------------- | -------------------------------------------- |
| sBOND → vBOND Converter | Converts sBOND into vBOND | `0xc393a58afe60b0cc0937613d4fcc47c205cfe3da` |
