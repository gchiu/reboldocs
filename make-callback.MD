USAGE:
     MAKE-CALLBACK action ffi-spec /abi abi-type

DESCRIPTION:
     Wrap function so it can be called in raw C code with a function pointer.
     MAKE-CALLBACK is a function .

RETURNS: [function!]

ARGUMENTS:
    action [function!]
        The existing Rebol function whose functionality is being wrapped
    ffi-spec [block!]
        Description of what C types each Rebol argument should map to

REFINEMENTS:
    /abi
        Specify the Application Binary Interface (vs. using default)
    abi-type [word!]
        'CDECL, 'FASTCALL, 'STDCALL, etc.
