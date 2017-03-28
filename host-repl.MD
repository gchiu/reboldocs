USAGE:
     HOST-REPL last-result last-failed focus-level focus-frame 

DESCRIPTION:
     Implements one Print-and-Read step of a Read-Eval-Print-Loop (REPL).
     HOST-REPL is a function .

RETURNS: [block! error!]
    Code to run or syntax error in the string input that tried to LOAD

ARGUMENTS:
    last-result [<opt> any-value!]
        The result from the last time HOST-REPL ran to display (if any)
    last-failed [logic!]
        TRUE if the last-result is an ERROR! that FAILed vs just a result
    focus-level [blank! integer!]
        If at a breakpoint, the integer index of how deep the stack was
    focus-frame [blank! frame!]
        If at a breakpoint, the function frame where the breakpoint was hit
