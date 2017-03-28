USAGE:
     COPY value /part limit /deep /types kinds

DESCRIPTION:
     Copies a series, object, or other value.
     COPY is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-value!]
        If an ANY-SERIES!, it is only copied from its current position

REFINEMENTS:
    /part
        Limits to a given length or position
    limit [any-number! any-series! pair!]
    /deep
        Also copies series values within the block
    /types
        What datatypes to copy
    kinds [typeset! datatype!]
