USAGE:
     LOAD-NATIVE spec impl index /body code /unloadable

DESCRIPTION:
     Load a native from a built-in extension
     LOAD-NATIVE is a function .

RETURNS: [function!]
    function value, will be created from the native implementation

ARGUMENTS:
    spec [block!]
        spec of the native
    impl [handle!]
        a handle returned from RX_Init_ of the extension
    index [integer!]
        Index of the native

REFINEMENTS:
    /body
    code [block!]
        User-equivalent body
    /unloadable
        The native can be unloaded later (when the extension is unloaded)
