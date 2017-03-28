USAGE:
     PROC spec body 

DESCRIPTION:
     Defines a user function with given spec and body and no return result.
     PROC is a function .

RETURNS: [function!]

ARGUMENTS:
    spec [block!]
        Help string (opt) followed by arg words (and opt type + string)
    body [block!]
        The body block of the function, use LEAVE to exit
