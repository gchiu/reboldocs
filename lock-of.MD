USAGE:
     LOCK-OF value 

DESCRIPTION:
     If value is already locked, return it...otherwise CLONE it and LOCK it.
     LOCK-OF is a specialization of LOCK .

ARGUMENTS:
    value [any-value!]
        Value to lock (will be locked deeply if an ANY-ARRAY!)
