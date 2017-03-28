USAGE:
     RECYCLE  /off /on /ballast size /torture /verbose

DESCRIPTION:
     Recycles unused memory.
     RECYCLE is a function .

RETURNS: [<opt> integer!]
    Number of series nodes recycled (if applicable)

REFINEMENTS:
    /off
        Disable auto-recycling
    /on
        Enable auto-recycling
    /ballast
        Trigger for auto-recycle (memory used)
    size [integer!]
    /torture
        Constant recycle (for internal debugging)
    /verbose
        Dump out information about series being recycled
