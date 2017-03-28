USAGE:
     NATIVE-ASSERT conditions /quiet

DESCRIPTION:
     Ensure conditions are TRUE? if hooked by debugging (see also: VERIFY)
     NATIVE-ASSERT is a function .

RETURNS: [<opt> logic! block!]
    Always returns void unless /QUIET is used to return failing blocks

ARGUMENTS:
    conditions [logic! block!]
        Single logic value or block of conditions to evaluate and test TRUE?

REFINEMENTS:
    /quiet
        Return failing condition as a BLOCK!, or BLANK! if success
