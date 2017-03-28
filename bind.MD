USAGE:
     BIND value target /copy /only /new /set

DESCRIPTION:
     Binds words or words in arrays to the specified context.
     BIND is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-array! any-word!]
        A word or array (modified) (returned)
    target [any-word! any-context!]
        The target context or a word whose binding should be the target

REFINEMENTS:
    /copy
        Bind and return a deep copy of a block, don't modify original
    /only
        Bind only first block (not deep)
    /new
        Add to context any new words found
    /set
        Add to context any new set-words found
