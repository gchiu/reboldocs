USAGE:
     AES  /key crypt-key iv /stream ctx data /decrypt

DESCRIPTION:
     Encrypt/decrypt data using AES algorithm.
     AES is a function .

RETURNS: [handle! binary! logic!]
    Stream cipher context handle or encrypted/decrypted data.

REFINEMENTS:
    /key
        Provided only for the first time to get stream HANDLE!
    crypt-key [binary!]
        Crypt key.
    iv [binary! blank!]
        Optional initialization vector.
    /stream
    ctx [handle!]
        Stream cipher context.
    data [binary!]
        Data to encrypt/decrypt.
    /decrypt
        Use the crypt-key for decryption (default is to encrypt)
