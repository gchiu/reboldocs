USAGE:
     APPLY value def 

DESCRIPTION:
     Invoke a function with all required arguments specified.
     APPLY is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    value [function! any-word! any-path!]
        Function or specifying word (preserves word name for debug info)
    def [block!]
        Frame definition block (will be bound and evaluated)
