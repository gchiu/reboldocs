USAGE:
     UNLOAD-EXTENSION-HELPER ext /cleanup cleaner

DESCRIPTION:
     Unload an extension
     UNLOAD-EXTENSION-HELPER is a function .

RETURNS: [<opt>]

ARGUMENTS:
    ext [object!]
        The extension to be unloaded

REFINEMENTS:
    /cleanup
    cleaner [handle!]
        The RX_Quit pointer for the builtin extension
