USAGE:
     REPEAT 'word value body 

DESCRIPTION:
     Evaluates a block a number of times or over a series.
     REPEAT is a function .

RETURNS: [<opt> any-value!]
    Last body result or BREAK value, will also be void if never run

ARGUMENTS:
    'word [word!]
        Word to set each time
    value [any-number! any-series! blank!]
        Maximum number or series to traverse
    body [block!]
        Block to evaluate each time
