USAGE:
     LIB-SET target value /opt /pad /lookback

DESCRIPTION:
     Sets a word, path, block of words, or context to specified value(s).
     LIB-SET is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    target [any-word! any-path! block! any-context!]
        Word, block of words, path, or object to be set (modified)
    value [<opt> any-value!]
        Value or block of values

REFINEMENTS:
    /opt
        Value is optional, and if no value is provided unset the target
    /pad
        For objects, set remaining words to NONE if block is too short
    /lookback
        Function uses evaluator lookahead to "look back" (see SET-INFIX)
