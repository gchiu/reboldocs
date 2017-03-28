USAGE:
     ARRAY size /initial value /local block rest

DESCRIPTION:
     Makes and initializes a series of a given size.
     ARRAY is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    size [integer! block!]
        Size or block of sizes for each dimension

REFINEMENTS:
    /initial
        Specify an initial value for all elements
    value
        Initial value (will be called each time if a function)
    /local
    block
    rest
