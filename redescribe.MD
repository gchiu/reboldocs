USAGE:
     REDESCRIBE spec value 

DESCRIPTION:
     Mutate function description with new title and/or new argument notes.
     REDESCRIBE is a function .

RETURNS: [function!]
    The input function, with its description now updated.

ARGUMENTS:
    spec [block!]
        Either a string description, or a spec block (without types).
    value [function!]
        (modified) Function whose description is to be updated.
