USAGE:
     MAKE-ACTION generator spec body 

DESCRIPTION:
     Internal generator used by FUNCTION and PROCEDURE specializations.
     MAKE-ACTION is a function .

RETURNS: [function!]

ARGUMENTS:
    generator [function!]
        Arity-2 "lower"-level function generator to use (e.g. FUNC or PROC)
    spec [block!]
        Help string (opt) followed by arg words (and opt type and string)
    body [block!]
        The body block of the function
