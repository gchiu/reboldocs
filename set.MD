USAGE:
     SET target value /opt /pad /lookback /any

DESCRIPTION:
     Sets a word, path, block of words, or context to specified value(s).
     SET is a function .

RETURNS: [<opt> any-value!]
    Just chains the input value (unmodified)

ARGUMENTS:
    target [any-word! any-path! block! any-context!]
        Word, block of words, path, or object to be set (modified)
    value [<opt> any-value!]
        Value or block of values

REFINEMENTS:
    /opt
        Value is optional, and if no value is provided then unset the word
    /pad
        For objects, set remaining words to NONE if block is too short
    /lookback
        If value is a function, then make the bound word dispatch infix
    /any
        Deprecated legacy synonym for /opt
