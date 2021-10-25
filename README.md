# Rummykub-Probability
This code calculates the most probable hand to win after the tiles are dealed.
The calculation process is done by giving points to each sequence and choosing the highest score hand. 
- Every sequence waiting FOR 1 tile to the middle to be complete get extra 0.5 points. 
- Each sequence gets the point of that sequences length.
- Each length 2 sequences get 1 point
- Person with the okey tile gets extra 1 point

Known bugs:
1- Can't calculate 12 13 1 sequence.
2- sometimes gives very long same color sequences.



