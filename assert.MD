USAGE:
     ASSERT conditions /quiet

DESCRIPTION:
     Ensure conditions are TRUE? if hooked by debugging (see also: VERIFY)
     ASSERT is a hijacking of ASSERT .

ARGUMENTS:
    conditions [logic! block!]
        Single logic value or block of conditions to evaluate and test TRUE?

REFINEMENTS:
    /quiet
        Return failing condition as a BLOCK!, or BLANK! if success
