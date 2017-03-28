USAGE:
     SET-UDP-MULTICAST port group member /drop

DESCRIPTION:
     Join (or leave) an IPv4 multicast group
     SET-UDP-MULTICAST is a function .

RETURNS: [<opt>]

ARGUMENTS:
    port [port!]
        An open UDP port
    group [tuple!]
        Multicast group to join (224.0.0.0 to 239.255.255.255)
    member [tuple!]
        Member to add to multicast group (use 0.0.0.0 for INADDR_ANY)

REFINEMENTS:
    /drop
        Leave the group (default is to add)
