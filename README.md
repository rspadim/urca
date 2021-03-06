# urca
Pfaff/Stigler Unit Root and Cointegration Analysis R package

I recommend the companion book
http://www.amazon.com/Analysis-Integrated-Cointegrated-Time-Series/dp/0387759662
that I know you will enjoy.


## Warning

This is a work in progress...don't install this package (yet)! Use the one from
CRAN. Unless that is, you want to help, then please have at it.

## Intention

We're revising the package to enhance some of the numeric computations for
stability and efficiency along the lines suggested by Doornik and O'Brien in
their superb paper http://www.doornik.com/research/CointNum2_final.pdf.

Our variation will use a generalized SVD. Because Pfaff's package is so
comprehensive at handling trends, constants, etc., there are quite a few
details to work through but the basic idea looks solid.

We're starting with the `ca.jo` function first. Eventually, almost everywhere
you find the function `solve` in the source code will include new routines.

We intend to make the new code paths optional to make it easy to compare with
the standard Johansen procedure.



## Status

No code yet! But my notes are online and that was probably the hard part. See:

* https://github.com/bwlewis/urca/blob/master/notes-1.jpg
* https://github.com/bwlewis/urca/blob/master/notes-2.jpg
* https://github.com/bwlewis/urca/blob/master/notes-3.jpg

Code will follow soon I hope... I say that knowing that these changes are
three years late already!
