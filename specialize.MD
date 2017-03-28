USAGE:
     SPECIALIZE value def 

DESCRIPTION:
     Create a new function through partial or full specialization of another
     SPECIALIZE is a function .

RETURNS: [function!]

ARGUMENTS:
    value [function! any-word! any-path!]
        Function or specifying word (preserves word name for debug info)
    def [block!]
        Definition for FRAME! fields for args and refinements
