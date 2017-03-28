USAGE:
     HOST-SCRIPT-PRE-LOAD is-module hdr 

DESCRIPTION:
     Code registered as a hook when a module or script are loaded
     HOST-SCRIPT-PRE-LOAD is a function .

ARGUMENTS:
    is-module [logic!]
    hdr [blank! object!]
        Header object (will be blank for DO of BINARY! with no header)
