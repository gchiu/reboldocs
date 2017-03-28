USAGE:
     left || right :lookahead

DESCRIPTION:
     Expression barrier that's willing to only run one expression after it
     || is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    left [<opt> <end> any-value!]
    right [<opt> any-value! <...>]
    :lookahead [any-value! <...>]
