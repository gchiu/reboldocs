USAGE:
     MAKE-ROUTINE lib name ffi-spec /abi abi-type

DESCRIPTION:
     Create a bridge for interfacing with arbitrary C code in a DLL
     MAKE-ROUTINE is a function .

RETURNS: [function!]

ARGUMENTS:
    lib [library!]
        Library DLL that function lives in (get with MAKE LIBRARY!)
    name [string!]
        Linker name of the function in the DLL
    ffi-spec [block!]
        Description of what C argument types the function takes

REFINEMENTS:
    /abi
        Specify the Application Binary Interface (vs. using default)
    abi-type [word!]
        'CDECL, 'FASTCALL, 'STDCALL, etc.
