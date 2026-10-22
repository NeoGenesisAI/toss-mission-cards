# toss-mission-cards

Remote card maps for Apps in Toss point missions (NeoGenesis).

`<appName>.json` lists that mini app's approved promotion cards: `[{"key", "promotionCode", "reward"}]`.
Builds that include the shared kit's `remote-cards.ts` read it at launch, so a newly approved card can be paid
without a new build. Data only; nothing here is executed.

Published by omp-toss-mission (`pj2/publish_card_maps.py`) from the paid-marketing ledger and the console listing.
