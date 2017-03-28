USAGE:
     GET source /opt /any

DESCRIPTION:
     Gets the value of a word or path, or values of a context.
     GET is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    source
        Word, path, context to get

REFINEMENTS:
    /opt
        The source may optionally have no value (allows returning void)
    /any
        Deprecated legacy synonym for /OPT
