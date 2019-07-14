# meleeforever
Using blockchain for automated tournament organization, payouts, player profiles, and stats.

## Data Structures

### Players
One player per wallet. A wallet contains the data records for that player.
* PlayerID (Wallet Key)
* Tag
* Elo
* Validated

### Tournaments
* TournamentID
* Title
* organizer privilege level
* Seed type (Elo / manual)
* Number of entrants
* Registration Start
* Registration End
* Launch Time
* Total prize pool
* Distribution
* Placement Result List
* Player set

### Brackets
* BracketID
* Title
* Bracket type 
* TournamentID

### Matches
* Match ID
* Timeout for DQ
* Status (Started/not started / completed)
* Players involved
* Result
* BracketID
* Winner advances to
* Loser advances to

### Team
* TeamID
* TeamTag
* PlayerList
* TeamElo

## Functionality
* Create a player
* Create a bracket
* Register into a bracket
* View bracket
* View match
* Post match results
* View the ladder
* Update player Elo

## Tokenomics
There is an initial supply of 0 tokens. Tokens are minted via the tournament creation process. When a tournament is hosted, a number of tokens is created equal to the square of the number of entrants. Upon tournament completion, newly minted tokens are distributed occording to the distribution map of that tournament. 

## Preventing Botting Tourneys
In order to qualify for token payouts, players must be validated through the validation process. The validation process consists of submitting a photo of ones self with a piece of paper with your tag written on it. Players that are already validated are able to view validation requests, and approve or deny. Upon getting 5 approvals, a player will become validated.

------------------------------------------------------

Suppose somebody enters cool tourny 12. 
Store the tourney data on the chain

## Features

Automatic DQ's


