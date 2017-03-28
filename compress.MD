USAGE:
     COMPRESS data /part limit /gzip /only

DESCRIPTION:
     Compresses a string series and returns it.
     COMPRESS is a function .

RETURNS: [binary!]

ARGUMENTS:
    data [binary! string!]
        If string, it will be UTF8 encoded

REFINEMENTS:
    /part
    limit
        Length of data (elements)
    /gzip
        Use GZIP checksum
    /only
        Do not store header or envelope information ("raw")
