USAGE:
     left <| right

DESCRIPTION:
     Expression barrier that evaluates to left side but executes right.
     <| is a function .

RETURNS: [<opt> any-value!]
    Evaluative result of `left`.

ARGUMENTS:
    left [<opt> <end> any-value!]
        A single complete expression on the left.
    right [<opt> any-value! <...>]
        Any number of expressions on the right.
