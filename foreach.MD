USAGE:
     FOREACH 'vars data body 

DESCRIPTION:
     Evaluates a block for each value(s) in a series.
     FOREACH is a function .

RETURNS: [<opt> any-value!]
    Last body result or BREAK value, will also be void if never run

ARGUMENTS:
    'vars [word! block!]
        Word or block of words to set each time (local)
    data [any-series! any-context! map! blank! datatype!]
        The series to traverse
    body [block!]
        Block to evaluate each time
