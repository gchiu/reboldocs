USAGE:
     RESOLVE target source /only from /all /extend

DESCRIPTION:
     Copy context by setting values in the target from those in the source.
     RESOLVE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    target [any-context!]
        (modified)
    source [any-context!]

REFINEMENTS:
    /only
        Only specific words (exports) or new words in target
    from [block! integer!]
        (index to tail)
    /all
        Set all words, even those in the target that already have a value
    /extend
        Add source words to the target if necessary
