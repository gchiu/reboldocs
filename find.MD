USAGE:
     FIND series value /part limit /only /case /skip size /last /reverse /tail /match

DESCRIPTION:
     Searches for a value; for series returns where found, else blank.
     FIND is a function .

RETURNS: [any-series! blank! logic!]

ARGUMENTS:
    series [any-series! any-context! map! gob! bitset! typeset! blank!]
    value [<opt> any-value!]

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
        Returns the end of the series
    /match
        Performs comparison and returns the tail of the match
