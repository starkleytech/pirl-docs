# FAQ Validator

#### What is the minimum requierement for a validator ?
> *The absolute minimum requrements to run the validator node are described below. This settings are NOT recomended as this could lead to unstable node and you could end up getting slashed!! If running validator node with specs close to minimum you must monitor your node and set up warnings for load etc..*
>
>* Minimum: 10 GB RAM, 60 GB Storage, 4 CPU 
>* Recomended: 60 GB RAN, 300 GB Storage, 6 CPU
>* Public IP on validator node needed for basic setup. 
(More information will come on how to setup a secure validator with sentry nodes)
>* Stabile internet connection are required. The validator nodes plays a very important role by securing the network and we recommend renting VPS from providers with good infrastructure and not trying to set up at home. 
> ### [Read more about validators requierements here](../validator_guide/guides_how_to_validate.md) 

#### How does slashing works ?
>- Level 1: isolated unresponsiveness, i.e. being offline for an entire epoch. No slashing, only chilling.
>- Level 2: concurrent unresponsiveness or isolated equivocation. Slashes a very small amount of the stake and chills.
>- Level 3: misconducts unlikely to be accidental, but which do not harm the network's security to any large extent. Examples include concurrent equivocation or isolated cases of unjustified voting in GRANDPA. Slashes a moderately small amount of the stake and chills.
>- Level 4: misconduct that poses a serious security or monetary risk to the system, or mass collusion. Slashes all or most of the stake behind the validator and chills.
>
>[Reference research article about slashing](https://research.web3.foundation/en/latest/polkadot/slashing.html)

#### What is the validator reward amount ?
> We can calculate it precisely, it depend on the network staking rate. Validator will have minted coins plus 20% of the transfert fees ( 80% goes to decentralised treasury ). Rewards are calculated based on era points, which have a probabilistic component. In other words, there may be slight differences in your rewards from era to era, and even amongst validators in the active set at the same time. These variations should cancel out over a long enough timeline.

#### Can I get my coins back if I stake or create a validator ?
> Yes you can unlock them when you want, you will have to wait the cooldown period to get it credited in your wallet, actual waiting period is 28 days.
