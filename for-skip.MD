USAGE:
     FOR-SKIP 'word skip body 

DESCRIPTION:
     Evaluates a block for periodic values in a series
     FOR-SKIP is a function .

RETURNS: [<opt> any-value!]
    Last body result or BREAK value, will also be void if never run

ARGUMENTS:
    'word [word! blank!]
        Word that refers to the series, set to positions in the series
    skip [integer!]
        Number of positions to skip each time
    body [block!]
        Block to evaluate each time
