USAGE:
     REQUEST-FILE  /save /multi /file name /title text /filter list

DESCRIPTION:
     Asks user to select a file and returns full file path (or block of paths).
     REQUEST-FILE is a function .

RETURNS:
    (undocumented)

REFINEMENTS:
    /save
        File save mode
    /multi
        Allows multiple file selection, returned as a block
    /file
    name [file!]
        Default file name or directory
    /title
    text [string!]
        Window title
    /filter
    list [block!]
        Block of filters (filter-name filter)
