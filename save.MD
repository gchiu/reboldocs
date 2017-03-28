USAGE:
     SAVE where value /header header-data /all /length /compress method

DESCRIPTION:
     Saves a value, block, or other data to a file, URL, binary, or string.
     SAVE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    where [file! url! binary! string! blank!]
        Where to save (suffix determines encoding)
    value
        Value(s) to save

REFINEMENTS:
    /header
        Provide a REBOL header block (or output non-code datatypes)
    header-data [block! object! logic!]
        Header block, object, or TRUE (header is in value)
    /all
        Save in serialized format
    /length
        Save the length of the script content in the header
    /compress
        Save in a compressed format or not
    method [logic! word!]
        true = compressed, false = not, 'script = encoded string
