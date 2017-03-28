USAGE:
     WRITE-STDOUT value 

DESCRIPTION:
     Write text to standard output, or raw BINARY! (for control codes / CGI)
     WRITE-STDOUT is a function .

RETURNS: [<opt>]

ARGUMENTS:
    value [string! char! binary!]
        Text to write, if a STRING! or CHAR! is converted to OS format
