USAGE:
     MAKE-ROUTINE-RAW pointer ffi-spec /abi abi-type

DESCRIPTION:
     Create a bridge for interfacing with a C function, by pointer
     MAKE-ROUTINE-RAW is a function .

RETURNS: [function!]

ARGUMENTS:
    pointer [integer!]
        Raw address of function in memory
    ffi-spec [block!]
        Description of what C argument types the function takes

REFINEMENTS:
    /abi
        Specify the Application Binary Interface (vs. using default)
    abi-type [word!]
        'CDECL, 'FASTCALL, 'STDCALL, etc.
