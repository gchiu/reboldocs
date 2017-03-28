USAGE:
     DH-COMPUTE-KEY obj public-key 

DESCRIPTION:
     Computes key from a private/public key pair and the peer's public key.
     DH-COMPUTE-KEY is a function .

RETURNS: [binary!]
    Negotiated key

ARGUMENTS:
    obj [object!]
        The Diffie-Hellman key object
    public-key [binary!]
        Peer's public key
