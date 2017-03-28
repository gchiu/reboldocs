USAGE:
     RC4  /key crypt-key /stream ctx data

DESCRIPTION:
     Encrypt/decrypt data (modifies) using RC4 algorithm.
     RC4 is a function .

RETURNS: [handle!]
    Returns stream cipher context handle.

REFINEMENTS:
    /key
        Provided only for the first time to get stream HANDLE!
    crypt-key [binary!]
        Crypt key.
    /stream
    ctx [handle!]
        Stream cipher context.
    data [binary!]
        Data to encrypt/decrypt.
