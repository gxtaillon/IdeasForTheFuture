General Elections
==

Goal
 * Provide representative general elections with local representatives

draft.

Have the land split in 101 electoral circonscriptions. (100 representatives, 1 assembly president)
todo: prevent jerrymandering (by limiting geometricaly the shape of circonscriptions?)

During an election to determine who will be the elected representative for a circonscription, electors of a circonscription rate as many of their candidates as they wish with points from 1 (best) to n where n is the number of candidates in that circonscription.

Candidates and representatives may be a member of a party.

Winners are chosen as follows:
* Electors rate each candidate in their circonscription from 1 (best) to n (worst)
 * n is the total number of candidates in the circonscription
* The score of a candidate is the sum of the multiplicative inverse of each of its ratings.
 * (1/r<sub>1</sub>+1/r<sub>2</sub>+...+1/r<sub>n</sub>)
* The score of a party is the sum of all its candidate's scores
* The score of the election is the sum of all candidate scores
* Parties receive seats by their score divided by the election score floored
* Each seat must be filled in decreasing order of candidate score percentage
 * Candidate score percentage is the candidate score divided by its circonscription's score
 * In other words, the candidates with the highest percentages scores in their circonscription are chosen to occupy their party's seats
* The government is the party with the most representatives
