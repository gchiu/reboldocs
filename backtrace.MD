USAGE:
     BACKTRACE level /limit frames /brief

DESCRIPTION:
     Backtrace to find a specific FRAME!, or other queried property.
     BACKTRACE is a function .

RETURNS: [<opt> block! frame!]
    Nothing if printing, if specific level a frame! else block

ARGUMENTS:
    level [<end> blank! integer! function!]
        Stack level to return frame for (blank to list)

REFINEMENTS:
    /limit
        Limit the length of the backtrace
    frames [blank! integer!]
        Max number of frames (pending and active), blank for no limit
    /brief
        Do not list depths, just function labels on one line
