USAGE:
     CHAIN pipeline /quote

DESCRIPTION:
     Create a processing pipeline of functions that consume the last's result
     CHAIN is a function .

RETURNS: [function!]

ARGUMENTS:
    pipeline [block!]
        List of functions to apply.  Reduced by default.

REFINEMENTS:
    /quote
        Do not reduce the pipeline--use the values as-is.
