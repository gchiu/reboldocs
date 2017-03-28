USAGE:
     CONSTRUCT spec body /only

DESCRIPTION:
     Creates an ANY-CONTEXT! instance
     CONSTRUCT is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    spec [datatype! block! any-context!]
        Datatype to create, specification, or parent/prototype context
    body [block! any-context! blank!]
        keys and values defining instance contents (bindings modified)

REFINEMENTS:
    /only
        Values are kept as-is
