# 1828 Differences

## Private Auction

* Companies are divided into multiple tiers, based on price.
* In turn order, each player will take one of the following actions:
  * Buy a private company.
    * Only allowed if the company has no current bids, is in the lowest tier, and is all other companies in that tier have bids.
    * Triggers all other private companies to be resolved in price order (until a company without bids is found) with auctions among the current bidders.
  * Bid on a private company
    * Only allowed if you cannot buy it outright.
  * Pass
    * You can still act in following turns after passing.

## Stock Round

* Order: Sell-Buy-Sell
* For buy action, can do one of the following:
  * Buy a single stock from the IPO or bank pool
  * Buy two stocks of their own corporation whose price is in the grey
  * Merge two corporations
  * Exchange MOHAWK & HUDSON private company for any 10% share of a corporation.
* Order in subsequent stock rounds is in the order that players starting passing in the previous stock round.
* Ownership limit: 60% per corporation
* Par prices are fixed based on game phase.
* After a D train is sold, new companies may not be parred, and their reserved spots for stations are filled with blockers.
* Companies use the standard IPO rules for their initial sale of stock (i.e. not the treasury rules some other 18xx games do).

## Operating Rounds

Operating rounds in 1828 work basically the same as 1830.
What follows is just a list of quirks.

* Corporations may place two tiles on a turn, but only one of those may be an upgrade.
* Virginia Coalfields and Coal Tokens
  * No stations may be placed on the coalfields tile (K11).
  * Only tile #4 (straight through with town) may be played on the Virginia Tunnel (K13). Any corporation placing this tile may take this tile's coal token.
  * If a corporation can connect to the Virginia Coalfields (K11), they may pay $120 for one of this tile's two coal tokens.
  * The Virginia Coalfields (K11) will block construction past it, and trains may not go to or through it, unless a corporation owns a coal token.
  * Each corporation may only have one coal token. If one comes to possess multiple, extras must be returned to the Virginia Coalfields (K11)
* COBOURG & PETERBOROUGH RAILWAY (private company)
  * This is a private company that pretends to be a public corporation.
  * During the private company portion of operating rounds, C&P may lay a single track, using money from its own treasury if needed.
  * Instead of a static revenue, C&P may run a (mechanically imaginary) 2-train from its initial station, paying half of the money earned to owner and half of the money earned into C&P's treasury.
  * Upon acquisition by a corporation, the money in C&P's treasury is passed to the corporation, and C&P's station may be swapped for the acquiring corporation's station.
    * The swap may not occur on a turn that the acquiring corporation has already placed a station.
  * If C&P closes or its station is not swapped in an acquisition, it's station is replaced with a blocker.
* BOSTON & MAINE and NEW YORK NEW HAVEN & HARTFORD
  * These two corporations (or systems that contain them) may place an additional track at a cost of $40 if they have not upgraded any track on this turn.

## Mergers

* Two public corporations may be merged into a system.
  * Notably, this means that a system cannot itself be merged into another system.
* The directors of both corporations must agree to this merger.
* One of two preconditions must be met:
  * Both corporations must have been floated in a previous stock round.
  * Both corporations cannot have been floated in a previous stock round, but one or both must have been floated in the current stock round.
* Merger process
  1. The acting player must select which corporation will remain as the system (i.e. which corporation will appear on the stock market, and which corporation's stations and shares will be used by the system.)
  2. The new system's stock price will be (roughly) the greater corporation's stock price plus half the lesser corporation's stock price.
  3. Combine the two corporation's assets.
     * If only one of the corporations has not floated, the money it would have gained on floating is lost.
     * If the system has multiple coal tokens, return all but one to the Virginia Coalfields.
     * Station markers of the other corporation are replaced with station markers of the new system.
       * If both corporations have a station on one tile, the active player will pick one to stay, and the other will return to the system's charter and be replaced with a blocker.
     * Each of the merged corporations' "shells" continue to have their own trains independently of one another.
  4. Players, in turn order starting with the active player, trade all pairs of either and/or both corporations shares for single shares of the new system.
     * Director's shares count as a pair for this purpose.
  5. Players, in turn order starting with the next player, must either:
     * Trade their remaining share, plus the difference between the current share price and the new merged share price for a share of the new system.
     * Discard their share in exchange for the current share price from the bank.
  6. All remaining IPO or bank pool shares of the merged corporations are discarded, and any remaining shares of the new system are placed into the bank pool.
  7. The new director must donate a 10% share to the new system's treasury.
     * If there is no director, or the director cannot make this donation, the merger fails.
  8. If one of the merged corporations has not floated, the resulting system will not have floated unless at least 60% of its shares have been sold.
* After a merger, the system will now have two "shell" corporations, which will have their own trains, subject to their own train limits, and thus will be forced to buy trains independently from one another, but will run trains and earn money together as one system. The system can reorganize these trains between the shells as they wish before buying trains.
* The donated share of the system in the system's treasury will pay out to the system.

## End Game

1828 has the following end game conditions.

* If a player bankrupts, the game ends immediately.
* If a corporation reaches $500 per stock, at the end of the current Stock or Operating Round.
* After a complete set of Operating Rounds after a D train is sold, the game ends.
