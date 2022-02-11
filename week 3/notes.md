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