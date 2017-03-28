USAGE:
     EXIT  /with value /from level

DESCRIPTION:
     Leave enclosing function, or jump /FROM.
     EXIT is a function .

RETURNS:
    (undocumented)

REFINEMENTS:
    /with
        Result for enclosing state (default is no value)
    value [any-value!]
    /from
        Jump the stack to return from a specific frame or call
    level [frame! function! integer!]
        Frame, function, or stack index to exit from
