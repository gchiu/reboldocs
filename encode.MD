USAGE:
     ENCODE type data /options opts

DESCRIPTION:
     Encodes a datatype (e.g. image!) into a series of bytes.
     ENCODE is a function .

RETURNS: [binary!]

ARGUMENTS:
    type [word!]
        Media type (jpeg, png, etc.)
    data
        The data to encode

REFINEMENTS:
    /options
        Special encoding options
    opts [block!]
