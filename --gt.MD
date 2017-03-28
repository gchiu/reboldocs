USAGE:
     :args -> :body

DESCRIPTION:
     Convenience variadic wrapper for FUNC and FUNCTION constructors
     -> is a function .

RETURNS: [function!]

ARGUMENTS:
    :args [<end> word! path! block!]
        Block of argument words, or a single word (passed via LIT-WORD!)
    :body [any-value! <...>]
        Block that serves as the body or variadic elements for the body

REFINEMENTS:
    /only
        Use FUNC and do not run locals-gathering on the body
