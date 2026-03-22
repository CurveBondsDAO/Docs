# scbdETH Contract Architecture

The scbdETH system mirrors the structure of sCBD, adapted for ETH-based assets.

#### 1. cbdETH Token

cbdETH is a non-yield-bearing ETH derivative that acts as the base asset.

* Soft-pegged to ETH
* Backed by ETH-denominated positions
* Minted and managed by the DAO

***

#### 2. scbdETH Token

A yield-bearing token representing a claim on underlying cbdETH.

* Users deposit cbdETH → receive scbdETH
* Value increases over time as yield accrues
* Redeemable back into cbdETH at an increasing rate

This structure allows yield to compound directly into the token price.

***

#### 3. Curve ETH Stable Pools

Curve pools composed of cbdETH, scbdETH, and other ETH derivatives provide liquidity and price discovery.

These pools:

* Enable efficient entry/exit
* Maintain peg stability
* Reflect accumulated yield in pricing

***

#### 4. DAO Treasury and Strategy Layer

The DAO actively allocates ETH capital into yield strategies.

When demand increases:

* Mint cbdETH
* Deploy ETH into Curve strategies
* Allocate across ETH pools

When demand decreases:

* Withdraw from strategies
* Rebalance cbdETH liquidity
* Maintain system stability

***
