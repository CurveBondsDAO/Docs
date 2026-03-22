# sCBD Contract Architecture

The sCBD system is composed of four primary components that together enable yield generation, liquidity, and protocol-controlled capital management.

#### 1. CBD Token

CBD is a non-yield-bearing stablecoin pegged to crvUSD.

It is minted and burned by the DAO and serves as the base asset underlying sCBD. CBD is designed to be interoperable across chains and supports controlled supply expansion based on protocol demand.

***

#### 2. sCBD Token

sCBD is a yield-bearing token representing a claim on underlying CBD.

It functions similarly to staking-based vault tokens, where users deposit CBD and receive sCBD in return. Over time, each sCBD represents an increasing amount of underlying CBD as yield is accrued.

sCBD can be redeemed back into CBD, with the conversion rate increasing as yield is distributed.

Additional CBD may be allocated to the sCBD contract by the protocol, which is then distributed proportionally to all sCBD holders.

***

#### 3. Curve Stable Pool

A Curve stable pool composed of scrvUSD, CBD, and sCBD provides liquidity and seamless user access.

This pool enables users to enter and exit positions through simple swaps, removing the need to interact directly with minting and redemption mechanics.

Pricing for sCBD is determined using its underlying asset ratio, allowing the pool to accurately reflect its increasing value as yield accrues.

***

#### 4. DAO Treasury and Control Layer

The DAO manages capital allocation and liquidity through its governance-controlled treasury.

When demand for CBD or sCBD increases, the DAO:

* mints new supply
* acquires scrvUSD
* deploys capital into yield-generating strategies

When users exit, the DAO:

* withdraws capital from strategies
* rebalances liquidity
* supports market stability

Yield generated from deployed capital is returned to the system and distributed to sCBD holders.

***

For a full list of deployed contracts and addresses, see the Contracts page.
