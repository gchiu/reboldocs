USAGE:
     MAP-EACH 'vars data body 

DESCRIPTION:
     Evaluate a block for each value(s) in a series and collect as a block.
     MAP-EACH is a function .

RETURNS: [block!]
    Collected block (BREAK/WITH can add a final result to block)

ARGUMENTS:
    'vars [word! block!]
        Word or block of words to set each time (local)
    data [block! vector!]
        The series to traverse
    body [block!]
        Block to evaluate each time
