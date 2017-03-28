USAGE:
     ENCLOAK data key /with

DESCRIPTION:
     Scrambles a binary string based on a key.
     ENCLOAK is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    data [binary!]
        Binary series to scramble (modified)
    key [string! binary! integer!]
        Encryption key or pass phrase

REFINEMENTS:
    /with
        Use a string! key as-is (do not generate hash)
