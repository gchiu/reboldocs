USAGE:
     COLLECT-WORDS block /deep /set /ignore hidden

DESCRIPTION:
     Collect unique words used in a block (used for context construction).
     COLLECT-WORDS is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    block [block!]

REFINEMENTS:
    /deep
        Include nested blocks
    /set
        Only include set-words
    /ignore
        Ignore prior words
    hidden [any-context! block!]
        Words to ignore
