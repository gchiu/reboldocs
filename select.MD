USAGE:
     SELECT series value /part limit /only /case /skip size /last /reverse /tail /match

DESCRIPTION:
     Searches for a value; returns the value that follows, else void.
     SELECT is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    series [any-series! any-context! map! blank!]
    value [any-value!]

REFINEMENTS:
    /part
        Limits the search to a given length or position
    limit [any-number! any-series! pair!]
    /only
        Treats a series value as only a single value
    /case
        Characters are case-sensitive
    /skip
        Treat the series as records of fixed size
    size [integer!]
    /last
        Backwards from end of series
    /reverse
        Backwards from the current position
    /tail
    /match
