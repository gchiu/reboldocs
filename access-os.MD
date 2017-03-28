USAGE:
     ACCESS-OS field /set value

DESCRIPTION:
     Access various OS functions (getuid, setuid, getpid, kill, etc.)
     ACCESS-OS is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    field [word!]
        uid, euid, gid, egid, pid

REFINEMENTS:
    /set
        To set or kill pid (sig 15)
    value [integer! block!]
        Argument, such as uid, gid, or pid (in which case, it could be
         a block with the signal number)
