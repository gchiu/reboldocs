USAGE:
     LIB-GET source /opt

DESCRIPTION:
     Gets the value of a word or path, or values of a context.
     LIB-GET is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    source [blank! any-word! any-path! any-context! block!]
        Word, path, context to get

REFINEMENTS:
    /opt
        Optionally return no value if the source is not SET?
