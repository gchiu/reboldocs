USAGE:
     ASSERT-DEBUG conditions /quiet /meta

DESCRIPTION:
     (undocumented)
     ASSERT-DEBUG is a function .

RETURNS: [<opt> any-value!]

ARGUMENTS:
    conditions [logic! block!]
        Conditions to check (or meta instructions if /META)

REFINEMENTS:
    /quiet
        Return void on success or a BLOCK! of the failure condition if failed
    /meta
        Block is enablement and disablement, e.g. [#heavy-checks on]
