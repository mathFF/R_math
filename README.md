# R_math
Syntax for basic and structured mathematical operations (algorithms) in R language. 
The codes was developed in R from the generic syntax of programs developed by Richard L. Burden and J. Douglas Faires 
in the course "Numeric Analysis", giving attention to the elementary math operations required to solve mathematical equations and functions.

Pseudocode

INPUT
NORM
{
function (x, type = c("O", "I", "F", "M", "2")) 
{
    if (identical("2", type)) {
        svd(x, nu = 0L, nv = 0L)$d[1L]
    }
    else .Internal(La_dlange(x, type))
}
}
SUM 
STOP
OUTPUT
SUM NORM
END
}

The norm shows the formal syntax of the norm operator for a given funtion in R Language.
