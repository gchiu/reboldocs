USAGE:
     TRANSCODE source /next /only /relax

DESCRIPTION:
     Translates UTF-8 binary source to values. Returns [value binary].
     TRANSCODE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    source [binary!]
        Must be Unicode UTF-8 encoded

REFINEMENTS:
    /next
        Translate next complete value (blocks as single value)
    /only
        Translate only a single value (blocks dissected)
    /relax
        Do not cause errors - return error object as value in place
