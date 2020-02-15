Insert the function you want to quadratise on the first line of "LHS.txt" in the format:

a1bibj....bk +/- a2blbm....bn +/- ...

On the second line insert a single number n, the number of auxiliaries you want to have in the quadratisation.

for example:

line1: b1b2b3b4b5 + 3b2b3b4 - 2b1b5b6b7
line2: 0

You can also add more functions with the same format in the following lines, e.g.

line1: b1b2b3b4b5 + 3b2b3b4 - 2b1b5b6b7
line2: 0
line3: b1b2b3b4 + 2b3b4b5b6
line4: 1
line5: b1b2b3b4b5b6 + b3b4b5b6b7b8
line6: 0
.
.
.

The results for each quadratisation are stored in the folder Quads in the files Quad0.txt, Quad1.txt, ...