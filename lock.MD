USAGE:
     LOCK value /clone

DESCRIPTION:
     Permanently lock values (if applicable) so they can be immutably shared.
     LOCK is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [any-value!]
        Value to lock (will be locked deeply if an ANY-ARRAY!)

REFINEMENTS:
    /clone
        Will lock a clone of the original (if not already immutable)
