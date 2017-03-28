USAGE:
     CHANGE series value /part limit /only /dup count

DESCRIPTION:
     Replaces element(s); returns just past the change.
     CHANGE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series! gob! port! struct!]
        At position (modified)
    value [<opt> any-value!]
        The new value

REFINEMENTS:
    /part
        Limits the amount to change to a given length or position
    limit [any-number! any-series! pair!]
    /only
        Only change a block as a single value (not the contents of the block)
    /dup
        Duplicates the change a specified number of times
    count [any-number! pair!]
