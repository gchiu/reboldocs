USAGE:
     CHECKSUM data /part limit /tcp /secure /hash size /method word /key key-value

DESCRIPTION:
     Computes a checksum, CRC, or hash.
     CHECKSUM is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    data [binary!]
        Bytes to checksum

REFINEMENTS:
    /part
    limit
        Length of data
    /tcp
        Returns an Internet TCP 16-bit checksum
    /secure
        Returns a cryptographically secure checksum
    /hash
        Returns a hash value
    size [integer!]
        Size of the hash table
    /method
        Method to use
    word [word!]
        Methods: SHA1 MD5 CRC32
    /key
        Returns keyed HMAC value
    key-value [any-string!]
        Key to use
