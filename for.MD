USAGE:
     FOR 'word start end bump body 

DESCRIPTION:
     Evaluate a block over a range of values. (See also: REPEAT)
     FOR is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    'word [word!]
        Variable to hold current value
    start [any-series! any-number!]
        Starting value
    end [any-series! any-number!]
        Ending value
    bump [any-number!]
        Amount to skip each time
    body [block!]
        Block to evaluate
