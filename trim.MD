USAGE:
     TRIM series /head /tail /auto /lines /all /with str

DESCRIPTION:
     Removes spaces from strings or blanks from blocks or objects.
     TRIM is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    series [any-series! object! error! module!]
        Series (modified) or object (made)

REFINEMENTS:
    /head
        Removes only from the head
    /tail
        Removes only from the tail
    /auto
        Auto indents lines relative to first line
    /lines
        Removes all line breaks and extra spaces
    /all
        Removes all whitespace
    /with
    str [char! string! binary! integer!]
        Same as /all, but removes characters in 'str'
