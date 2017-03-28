USAGE:
     RSA data key-object /decrypt /private /padding padding-type

DESCRIPTION:
     Encrypt/decrypt data using the RSA algorithm.
     RSA is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    data [binary!]
    key-object [object!]

REFINEMENTS:
    /decrypt
        Decrypts the data (default is to encrypt)
    /private
        Uses an RSA private key (default is a public key)
    /padding
        Selects the type of padding to use
    padding-type [word! blank!]
        Type of padding. Available values: PKCS1 or NONE
