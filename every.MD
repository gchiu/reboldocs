USAGE:
     EVERY 'vars data body 

DESCRIPTION:
     Returns last TRUE? value if evaluating a block over a series is all TRUE?
     EVERY is a function .

RETURNS: [<opt> any-value!]
    TRUE or BLANK! collected, or BREAK value, TRUE if never run.

ARGUMENTS:
    'vars [word! block!]
        Word or block of words to set each time (local)
    data [any-series! any-context! map! blank! datatype!]
        The series to traverse
    body [block!]
        Block to evaluate each time
