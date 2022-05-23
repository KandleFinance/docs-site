# How does Kandle work?

## Overview
Kandle is a seductive and decentralized finance (DeFi) platform for traders who like to be generously rewarded.
 It’s a pool-driven ecosystem that ensures to create value from the engaged pool tokens and the number of transactions being made on the blockchain network.

![Kandle Eco System](/assets/images/kandle_ecosystem.svg "Kandle Eco System")

## What is a Pool?
We can define a pool as a fixed period of time where kandlers engage some of their tokens to get rewarded at the
end of this period. A new pool means a new burning event and the burned tokens amount is dependent on the total
engaged tokens.

## Kandle Collectors

The whole process is being managed by collectors and each collector is a wallet that plays a specific role in the
ecosystem. *Why a wallet?* to **give more transparency to the holders and traders** as all transactions and events in that
wallet are traced.

- **Fees collector**: collects all fees gathered from transactions.
- **Ashes collector**:  gathers all pool engaged tokens.
- **Burns collector**: collects discarded tokens to be burned at the end of a pool.
- **Rewards collector**: receives all the tokens that will be shared between kandlers to reward them for participating
in the pool.
- **Fuel collector**: collects the rewarding transaction fees and the pool residue tokens after the rewarding process is done.
This collector is a backup source of rewards, it refuels the rewards collector during the rewarding process upon
kandlers' request. It also refuels the staking collector after each pool to reload continuously the rewards to be shared
between stakers.
- **Staking collector**: receives and shares constantly rewards between stakers.