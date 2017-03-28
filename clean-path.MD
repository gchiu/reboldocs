USAGE:
     CLEAN-PATH file /only /dir

DESCRIPTION:
     Returns new directory path with `//` `.` and `..` processed.
     CLEAN-PATH is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    file [file! url! string!]

REFINEMENTS:
    /only
        Do not prepend current directory
    /dir
        Add a trailing / if missing
