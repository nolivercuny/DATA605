# Notes

Eigenvector = vector that is scaled up by a transformation

Vector is an object that has a magnitude and a direction. If you think of an x/y plane, it's like a line defined by how steep it is and which direction it's point e.g. up-to the right very steep

Converting a matrix to RREF means first converting it to REF using Guassian elmination
    Row Echelon Form must mean the following
        * All rows consisting of only zeroes are at the bottom.
        * The leading coefficient (also called the pivot) of a nonzero row is always strictly to the right of the leading coefficient of the row above it.

    Reduced Row Echelon Form adds additional criteria
        * The leading entry in each nonzero row is a 1 (called a leading 1).
        * Each column containing a leading 1 has zeros in all its other entries
Guassian elmination consists of three legal operations on the matrix

* Swap the positions of two rows.
* Multiply a row by a non-zero scalar.
* Add to one row a scalar multiple of another.

When you're finding the eigenspace/vector and you're on the step where you have the matrix in RREF and you set v1/v2/v3 equal to zero
Each row tells you the value you for v1,v2,v3. E.g. if in the first row you have [1,0,12]  = v1 + 12v3  = 0  = v1 = -12v3 = -1/12v1 = v3
if the second row is [0,1,2] = 1v2 + 2v3 = 0
last row is all zeros [0,0,0] means v3 = v3

then you solve for the first row in terms of v1 meaning v1 is on the left side and v3 should be on the right e.g. v1 = -2v3 = -1/2v1 = v3
and solve for the second row in terms of v2 meaning v2 is on the left and v3 should be on the right.