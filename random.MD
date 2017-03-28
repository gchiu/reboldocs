USAGE:
     RANDOM value /seed /secure /only

DESCRIPTION:
     Returns a random value of the same datatype; or shuffles series.
     RANDOM is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    value
        Maximum value of result (modified when series)

REFINEMENTS:
    /seed
        Restart or randomize
    /secure
        Returns a cryptographically secure random number
    /only
        Pick a random value from a series
