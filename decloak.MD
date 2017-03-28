USAGE:
     DECLOAK data key /with

DESCRIPTION:
     Decodes a binary string scrambled previously by encloak.
     DECLOAK is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    data [binary!]
        Binary series to descramble (modified)
    key [string! binary! integer!]
        Encryption key or pass phrase

REFINEMENTS:
    /with
        Use a string! key as-is (do not generate hash)
