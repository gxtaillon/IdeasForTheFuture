Continuous General Elections
==

draft.

Goals

 - Provide representative general elections
 - Provide finer grained control of government policies and officials

Side effects

 - Assign each circonscription their own MP
 - Remove jerrymandering concerns
  - No point in jerrymandering with representative general elections where votes are counted in the same common pool

Assert

- Have the land split in 101 electoral circonscriptions.
 - 100 Members of parliament
 - 1 assembly president
- Candidates and representatives may be a member of a party.
- Polls are held each week
- Electors vote during the week of their birth day only
- Ballot "unboxing" is recorded on video or on any media that allows the process to be audited in full by any citizen

Winners are chosen as follows

* Electors rate each candidate in their circonscription from 1 (best) to n (worst)
 * n is the total number of candidates in the circonscription
* The score of a candidate is the sum of the multiplicative inverse of each of its ratings.
 * (1/r<sub>1</sub>+1/r<sub>2</sub>+...+1/r<sub>k</sub>)
* The score of a party is the sum of all its candidate's scores
* The score of the election is the sum of all candidate scores
* Parties receive seats by their score divided by the election score floored
* Each seat must be filled in decreasing order of candidate score percentage
 * Candidate score percentage is the candidate score divided by its circonscription's score
 * In other words, the candidates with the highest percentages scores in their circonscription are chosen to occupy their party's seats
* The government is the party with the most representatives
 * Seats belong to parties and seats are given by scores, therefore if scores change after an election, seats must be recalculated and representatives repicked after a partial election using the latest scores of each circonscription
    * A score change can be
       * A representative leaving its role (quits politics,dies,jailed,etc.)
       * A representative leaving its party
    * A partial election is an election limited to a single circonscription which no longer has a sitting representative
    * The latest scores are the scores from the previous election (partial or general)

