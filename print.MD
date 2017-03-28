USAGE:
     PRINT value /only /eval

DESCRIPTION:
     Textually output value (evaluating elements if a block), adds newline
     PRINT is a function .

ARGUMENTS:
    value [any-value!]
        Value or BLOCK! literal (BLANK! means print nothing)

REFINEMENTS:
    /only
        Do not add a newline, and do not implicitly space items if a block
    /eval
        Allow value to be a block and evaluated (even if not literal)
