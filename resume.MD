USAGE:
     RESUME  /with value /do code /at level

DESCRIPTION:
     Resume after a breakpoint, can evaluate code in the breaking context.
     RESUME is a function .

RETURNS:
    (undocumented)

REFINEMENTS:
    /with
        Return the given value as return value from BREAKPOINT
    value [any-value!]
        Value to use
    /do
        Evaluate given code as return value from BREAKPOINT
    code [block!]
        Code to evaluate
    /at
        Return from another call up stack besides the breakpoint
    level [frame! function! integer!]
        Stack level to target in unwinding (can be BACKTRACE #)
