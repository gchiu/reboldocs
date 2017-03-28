USAGE:
     SET-UDP-TTL port ttl 

DESCRIPTION:
     Set the TTL of a UDP port
     SET-UDP-TTL is a function .

RETURNS: [<opt>]

ARGUMENTS:
    port [port!]
        An open UDP port
    ttl [integer!]
        0 = local machine only, 1 = subnet (default), or up to 255
