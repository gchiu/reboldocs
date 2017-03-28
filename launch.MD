USAGE:
     LAUNCH script /args arg /wait

DESCRIPTION:
     Runs a script as a separate process; return immediately.
     LAUNCH is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    script [file! string! blank!]
        The name of the script

REFINEMENTS:
    /args
    arg [string! block! blank!]
        Arguments to the script
    /wait
        Wait for the process to terminate
