USAGE:
     APPEND series value /part limit /only /dup count

DESCRIPTION:
     Inserts element(s) at tail; for series, returns head.
     APPEND is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series! port! map! gob! object! module! bitset!]
        Any position (modified)
    value [<opt> any-value!]
        The value to insert

REFINEMENTS:
    /part
        Limits to a given length or position
    limit [any-number! any-series! pair!]
    /only
        Only insert a block as a single value (not the contents of the block)
    /dup
        Duplicates the insert a specified number of times
    count [any-number! pair!]
