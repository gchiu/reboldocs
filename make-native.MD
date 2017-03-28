USAGE:
     MAKE-NATIVE spec source /linkname name

DESCRIPTION:
     Create a "user native" function compiled from C source
     MAKE-NATIVE is a function .

RETURNS: [function!]
    Function value, will be compiled on demand or by COMPILE

ARGUMENTS:
    spec [block!]
        The spec of the native
    source [string!]
        C source of the native implementation

REFINEMENTS:
    /linkname
        Provide a specific linker name
    name [string!]
        Legal C identifier (default will be auto-generated)
