# LBS-8queens

Local Beam Search for 8 Queens

Test by Python 2.7

Goal states are states that have 0 pairs of attacking queens
Queens in same row or column or diagonal are attacking queens

Search Algorithm:
1.Start with k randomly generated states
2.At each iteration, all the successors of all k states are generated
3.If any one is a goal state, stop; else select the k best successors from the complete list and repeat.
