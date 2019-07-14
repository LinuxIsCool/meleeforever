# meleeforever
Using blockchain for automated tournament organization, payouts, player profiles, and stats.

## Data Structures

### Players
One player per wallet. A wallet contains the data records for that player.
* PlayerID (Wallet Key)
* Tag
* Elo

### Tournaments
* TournamentID
* Title
* organizer privilege level
* Seed type (Elo / manual)
* Number of entrants
* Registration Start
* Registration End
* Launch Time
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

------------------------------------------------------

Suppose somebody enters cool tourny 12. 
Store the tourney data on the chain

## Features

Automatic DQ's


