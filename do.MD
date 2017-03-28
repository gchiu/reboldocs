USAGE:
     DO source /args arg /next var /only

DESCRIPTION:
     Evaluates a block of source code (directly or fetched according to type)
     DO is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    source [<opt> blank! block! string! binary! url! file! tag! error! function! frame!]

REFINEMENTS:
    /args
        If value is a script, this will set its system/script/args
    arg
        Args passed to a script (normally a string)
    /next
        Do next expression only, return it, update block variable
    var [any-word! blank!]
        If not blank, then a variable updated with new block position
    /only
        Don't catch QUIT (default behavior for BLOCK!)
