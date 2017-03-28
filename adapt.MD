USAGE:
     ADAPT adaptee prelude 

DESCRIPTION:
     Create a variant of a function that preprocesses its arguments
     ADAPT is a function .

RETURNS: [function!]

ARGUMENTS:
    adaptee [function! any-word! any-path!]
        Function or specifying word (preserves word name for debug info)
    prelude [block!]
        Code to run in constructed frame before adapted function runs
