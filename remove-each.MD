USAGE:
     REMOVE-EACH 'vars data body 

DESCRIPTION:
     Removes values for each block that returns true; returns removal count.
     REMOVE-EACH is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    'vars [word! block!]
        Word or block of words to set each time (local)
    data [any-series!]
        The series to traverse (modified)
    body [block!]
        Block to evaluate (return TRUE to remove)
