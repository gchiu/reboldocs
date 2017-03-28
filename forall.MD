USAGE:
     FORALL 'word body 

DESCRIPTION:
     Evaluates a block for each position until the end, using NEXT to skip
     FORALL is a specialization of FOR-SKIP .

ARGUMENTS:
    'word [word! blank!]
        Word that refers to the series, set to positions in the series
    body [block!]
        Block to evaluate each time
