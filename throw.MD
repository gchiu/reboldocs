USAGE:
     THROW value /name name-value

DESCRIPTION:
     Throws control back to a previous catch.
     THROW is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [<opt> any-value!]
        Value returned from catch

REFINEMENTS:
    /name
        Throws to a named catch
    name-value [word! function! object!]
