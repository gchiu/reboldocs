USAGE:
     PAUSE :code 

DESCRIPTION:
     Pause in the debugger before running the provided code
     PAUSE is a function .

RETURNS: [<opt> any-value!]
    Result of the code evaluation, or RESUME/WITH value if override

ARGUMENTS:
    :code [group!]
        Run the given code if breakpoint does not override
