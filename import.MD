USAGE:
     IMPORT module /version ver /check sum /no-share /no-lib /no-user

DESCRIPTION:
     Imports a module; locate, load, make, and setup its bindings.
     IMPORT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    module [word! file! url! string! binary! module! block!]

REFINEMENTS:
    /version
    ver [tuple!]
        Module must be this version or greater
    /check
    sum [binary!]
        Match checksum (must be set in header)
    /no-share
        Force module to use its own non-shared global namespace
    /no-lib
        Don't export to the runtime library (lib)
    /no-user
        Don't export to the user context
