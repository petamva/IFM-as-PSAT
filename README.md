# IFM-as-PSAT
## Modeling the Inverse Frequent Mining problem as a Probabilistic Satisfiability Instance 

A collection (C) of a transaction's database (T) itemset-support pairs can be modeled in PSAT terms as a 
consistent collection of constraints over T based on which we can reconstruct T. The pairs in C can be 
seen as the set of logical statements (clauses) and the set of all possible transactions over the set of 
items (I) belonging to the database as the truth assignments.

For the needs of the problem, synthetic datasets have been constructed in R, via the random.transactions function
of the arules package by Michael Hahsler.
