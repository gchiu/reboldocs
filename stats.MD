USAGE:
     STATS  /show /profile /timer /evals /dump-series pool-id

DESCRIPTION:
     Provides status and statistics information about the interpreter.
     STATS is a function .

RETURNS:
    (undocumented)

REFINEMENTS:
    /show
        Print formatted results to console
    /profile
        Returns profiler object
    /timer
        High resolution time difference from start
    /evals
        Number of values evaluated by interpreter
    /dump-series
        Dump all series in pool
    pool-id [integer!]
        -1 for all pools
