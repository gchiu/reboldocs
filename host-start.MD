USAGE:
     HOST-START argv boot-embedded boot-exts 

DESCRIPTION:
     Loads extras, handles args, security, scripts.
     HOST-START is a function .

RETURNS: [integer! function!]
    If integer, host should exit with that status; else a REPL FUNCTION!

ARGUMENTS:
    argv [block!]
        Raw command line argument block received by main() as STRING!s
    boot-embedded [binary! string! blank!]
        Embedded user script inside this host instance (e.g. encapping)
    boot-exts [block! blank!]
        Extensions (modules) loaded at boot
