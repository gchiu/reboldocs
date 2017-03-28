USAGE:
     EVAL value /only

DESCRIPTION:
     (Special) Process received value *inline* as the evaluator loop would.
     EVAL is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [<opt> any-value!]
        BLOCK! passes-thru, FUNCTION! runs, SET-WORD! assigns...

REFINEMENTS:
    /only
        Suppress evaluation on any ensuing arguments value consumes
