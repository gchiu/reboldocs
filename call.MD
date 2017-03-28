USAGE:
     CALL command /wait /console /shell /info /input in /output out /error err

DESCRIPTION:
     Run another program; return immediately (unless /WAIT).
     CALL is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    command [string! block! file!]
        An OS-local command line (quoted as necessary), a block with
         arguments, or an executable file

REFINEMENTS:
    /wait
        Wait for command to terminate before returning
    /console
        Runs command with I/O redirected to console
    /shell
        Forces command to be run from shell
    /info
        Returns process information object
    /input
        Redirects stdin to in
    in [string! binary! file! blank!]
    /output
        Redirects stdout to out
    out [string! binary! file! blank!]
    /error
        Redirects stderr to err
    err [string! binary! file! blank!]
