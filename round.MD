USAGE:
     ROUND value /to scale /even /down /half-down /floor /ceiling /half-ceiling

DESCRIPTION:
     Rounds a numeric value; halves round up (away from zero) by default.
     ROUND is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-number! pair! money! time!]
        The value to round

REFINEMENTS:
    /to
        Return the nearest multiple of the scale parameter
    scale [any-number! money! time!]
        Must be a non-zero value
    /even
        Halves round toward even results
    /down
        Round toward zero, ignoring discarded digits. (truncate)
    /half-down
        Halves round toward zero
    /floor
        Round in negative direction
    /ceiling
        Round in positive direction
    /half-ceiling
        Halves round in positive direction
