# Migration FAQ

#### We have until when to claim for yours Pirl 2.0 ?

>There is no time limit set.

#### Do I need to disable the masternode to get my claim in Pirl 2.0 ?
> No, you will get your coins even if they are locked in the contract.

#### Does wPIRL need to be bridged back to pirl legacy chain for swap of coins? 
> Yes, you need to bridge all your coins back to be able to swap your PIRL. After the snapshot it's not possible until we re-implemented it. No date or schedule yet.

#### Is Ledger or any hardware wallet supported at the start of the new chain ? 
> Not at the beginning but we will support hardware wallets at a later stage. No date or schedule yet.

#### If I keep my PIRL on the exchange, is the change to the new blockchain automatic ?
> Yes, the exchanges will swap your PIRL automatically. (Please don´t hold your coins longer at any exchange, not your keys, not your coins)

#### What should I do to switch to pirl 2.0 ?
> You can swap your old Pirl for new Pirl 2.0 by following [this tutorial](../migrate/claims_coins.md)

#### I used the web wallet, I'm safe for the claim ?
> Yes, You can swap your old Pirl for new Pirl 2.0 by following [this tutorial](../migrate/claims_coins.md)

#### Can I claim my coins with ledger wallet ?
> Yes, be sure to have backup phrase and latest firmware.

#### I didn't unlocked the coins locked in masternode contract, are they lost ?
> No, the coins locked in the masternode contract(s) will be available freely in your wallet after the fork in the new network.

### How to delete all the old Pirl services on masternodes ?
> <strong>MAKE SURE YOU ARE NOT STORING YOUR WALLET KEYS ON VPS/SERVER BEFORE CONTINUE!! </strong>

> ``` service pirl stop && service marlin stop && rm -rf /root/.pirl && rm -rf /root/.marlin && systemctl disable pirl && systemctl disable marlin ```