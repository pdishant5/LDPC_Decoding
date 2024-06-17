# LDPC_Decoding
This is a group project with group size 10. I have worked on all the aspects of the project with my group members.

This project aims to implement an efficient algorithm performing LDPC decoding on MATLAB, for both, Soft and Hard Decision Decoding. We use the Binary Phase-Shift Keying (BPSK) modulation to modulate the transmitted message. And also BPSK demodulation for demodulating purpose.

Low Density Parity Check decoding is used often in the communication thoery for the transmission of encoded messages.

There are two types of nodes to represent decoding process. Check nodes and Variable Nodes. As the names suggest, the variable nodes are the received message that we want to decode and the check nodes are the nodes that we use to check if the currently decoded message can be correct. Check nodes are formed by taking some number of variable nodes and the sum of all those nodes modulo two should be zero for the message to be possibly correctly decoded. Low Density Parity Code implies that the number of variable nodes connected to a check node is very less compared to the total length of the transmitted message (total number of variable node). We can use Tanner Graph representations for the same. So, in other words, the degree of check nodes and variable nodes is very less as compared to the number of nodes. Hence these codes are called Low Density Parity Check Codes as their parity check matrix has very few 1s as compared to 0s.

We have implemented the decoding algorithm in MATLAB using hash tables and maps.

To get the accurate result, we have performed Monte Carlo simulations over the experiment and final expected probability has been calculated.

# Contents:
Hard Decision Decoding MATLAB code.
Soft Decision Decoding MATLAB code.
Hard Decision Decoding Results.
Soft Decision Decoding Results.
Two large matrices to check the working of the code (NR_1_5_352 and NR_2_6_52).
One dummy 9 x 12 H-matrix.
Bit error probability simulations for both hard and soft decision decoding.

# DSA- concepts used
Graph Traversal.
Hash/Unordered map.
