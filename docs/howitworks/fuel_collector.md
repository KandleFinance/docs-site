# Fuel Collector

The Fuel collector plays a big role in managing tokens within
the pool. The way our rewarding process is developed
makes it common in some pools to have left unrewarded
tokens, called residue. This residue is collected by the Fuel
Collector and will be recovered by the Rewards collector if
some conditions are met during [the rewarding process](rewarding_process.md).

!!! note

    The Fuel collector will also be used to refuel the Staking
    collector with tokens that will be shared between stakers.
    The *Staking collector* main role and the staking process will
    be discussed in upcoming versions of the documentation.

<figure markdown>
![Fees Mechanism](/assets/images/fuel_collector.svg "Fuel Collector")
</figure>

--8<-- "includes/abbreviations.md"