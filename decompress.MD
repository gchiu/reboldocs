USAGE:
     DECOMPRESS data /part lim /gzip /limit max /only

DESCRIPTION:
     Decompresses data.
     DECOMPRESS is a function .

RETURNS: [binary!]

ARGUMENTS:
    data [binary!]
        Data to decompress

REFINEMENTS:
    /part
    lim
        Length of compressed data (must match end marker)
    /gzip
        Use GZIP checksum
    /limit
    max
        Error out if result is larger than this
    /only
        Do not look for header or envelope information ("raw")
