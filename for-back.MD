USAGE:
     FOR-BACK 'word body 

DESCRIPTION:
     Evaluates a block for each position until the start, using BACK to skip
     FOR-BACK is a specialization of FOR-SKIP .

ARGUMENTS:
    'word [word! blank!]
        Word that refers to the series, set to positions in the series
    body [block!]
        Block to evaluate each time
