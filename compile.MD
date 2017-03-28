USAGE:
     COMPILE natives /options flags

DESCRIPTION:
     Compiles one or more native functions at the same time, with options.
     COMPILE is a function .

RETURNS: [<opt>]

ARGUMENTS:
    natives [block!]
        Functions from MAKE-NATIVE or STRING!s of code.

REFINEMENTS:
    /options
    flags [block!]
        
         The block supports the following dialect:
         include [block! path!]
             "include path"
         define [block!]
             {define preprocessor symbols as "VAR=VAL" or "VAR"}
         debug
             "Add debugging information to the generated code?"
     
