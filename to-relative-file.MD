USAGE:
     TO-RELATIVE-FILE file /no-copy /as-rebol /as-local

DESCRIPTION:
     Returns relative portion of a file if in subdirectory, original if not.
     TO-RELATIVE-FILE is a function .

RETURNS: [file! string!]

ARGUMENTS:
    file [file! string!]
        File to check (local if string!)

REFINEMENTS:
    /no-copy
        Don't copy, just reference
    /as-rebol
        Convert to REBOL-style filename if not
    /as-local
        Convert to local-style filename if not
