# Runoff
C code showing a runoff election

Description:
When compiling using ./runoff, the user is must include possible candidates to be voted on before initializing the program. They must input "./runoff (insert names)" or the program will break and the user will have to try again.

Once user has added names for the program, user will be prompted to input the number of voters that will be voting. Depending on the number of voters and candidates, user will be asked to vote the top choice, followed by the second choice, and so on for each voter. The top choice will be counted as a vote, and the candidate with the most votes will be output as the winner. Candidates with the lowest amount of votes will be eliminated from the running.

In the event of a tie, the program will show all the candidates who tied while candidates who did not earn enough votes will be eliminated.
