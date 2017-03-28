USAGE:
     INSERT series value /part limit /only /dup count

DESCRIPTION:
     Inserts element(s); for series, returns just past the insert.
     INSERT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series! port! map! gob! object! bitset! port!]
        At position (modified)
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
