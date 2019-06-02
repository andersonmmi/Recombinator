# Reloaner
Decentralized marketplace that allows microloans to be combined and repackaged an unlimited number of times.

## Core Concepts
Reloaner is a **game** built on the xDai network that allows borrowers to originate loans from a combination of loans and become a lender. This is an infinate game open in perpetuity to all agents capable of playing. 

The first goal of the game is to create a lively marketplace of loans where credit scores can be determined by 3rd parties through address nonce, win/loss ratios, repayments totals, default totals, and a variety of other methods that have yet to be discovered.

The second goal of the game is to study how individuals perform in different points in the supply chain. There are three different minigames in the supply chain: Origination, Combination, and Consumption; and two minigames in the metagame: Game Making and Bad Acting.

- Origination: A player creates a loan, sets an interest rate, and becomes a lender. The lender then sets minimum values for qualities that a consumer must possess in order for a consumer to claim that loan. For example, they could set conditions that a 5 xDai loan can be claimed if `{ consumer_address_nonce > 10 , win_loss_ratio < 0.6 , repayment_total >= 0 , default_total < 0 }` or if `{ consumer_address_nonce > 100 , win_loss_ratio > 0.9 , repayment_total >= 100 , default_total <= 8 }`.

- Combination: A consumer claims two loans and combines them into a complex loan, sets an interest rate equal to or greater than the aggregate intrest rate of the the combined loans, and becomes a lender. The lender then sets minimum values for qualities that a consumer must possess in order for a consumer to claim that loan. For example, they could set conditions that a 5 xDai loan can be claimed if `{ consumer_address_nonce > 10 , win_loss_ratio < 0.9 , repayment_total >= 100 , default_total < 100 }` or if `{ consumer_address_nonce > 200 , win_loss_ratio > 0.95 , repayment_total > 0 , default_total < 4 }`.

- Consumption: where a consumer claims a loan, but does not set any claim conditions so it cannot be claimed by any other party. Having the claim on the loan, the consumer has three options:

Case 1: Satisfy the loan by paying the interest to the loan within 24 hours.

Case 2: Withdraw the funds and then satisfy the loan by paying the principle plus interest to the loan within 24 hours.

Case 3: Combine this loan with another loan within 24 hours and become a lender.

- Game Making: Game Masters(GMs) manipulate the game environment to fill their pockets with sweet digital gold. They are, however, bound by the rules of the smartcontracts that handles the game logic and the laws of physics.

- Bad Acting: Break the contracts, kidnap the GMs, manipulate the market, hack the user interface, the world is your oyster here!

## Player Classes
There are five classes in this game and any player is capable of playing as any class at atny time!

- Originators: Seek to maximize profit by min/maxing interest rates and combination potential.
- Combinators: Seek to maximize profit by claiming at the loans at low rates and creating new loans that min/max interest rates and combination potential.
- Comsumers: Seek to maximize profit outside of this game by reassigning assets from this game.
- Game Masters: Seek to maximize profit by adjusting the combination fee within the range of 0.00% to 1.00% and by getting more players involved in this game.
- Bad Actors: Play the game, ???, then Profit!!!


