USAGE:
     LOOP count body 

DESCRIPTION:
     Evaluates a block a specified number of times.
     LOOP is a function .

RETURNS: [<opt> any-value!]
    Last body result or BREAK value, will also be void if never run

ARGUMENTS:
    count [any-number! logic! blank!]
        Repetitions (true loops infinitely, FALSE? doesn't run)
    body [block! function!]
        Block to evaluate or function to run (may be a BRANCHER).
