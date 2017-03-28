USAGE:
     TRACE mode /back /function

DESCRIPTION:
     Enables and disables evaluation tracing and backtrace.
     TRACE is a function .

RETURNS: [<opt>]

ARGUMENTS:
    mode [integer! logic!]

REFINEMENTS:
    /back
        Set mode ON to enable or integer for lines to display
    /function
        Traces functions only (less output)
