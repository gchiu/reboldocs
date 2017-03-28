USAGE:
     ALTER series value /case

DESCRIPTION:
     Append value if not found, else remove it; returns true if added.
     ALTER is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series! port! bitset!]
        (modified)
    value

REFINEMENTS:
    /case
        Case-sensitive comparison
