USAGE:
     REPLACE target pattern replacement /all /case /tail

DESCRIPTION:
     Replaces a search value with the replace value within the target series.
     REPLACE is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    target [any-series!]
        Series to replace within (modified)
    pattern
        Value to be replaced (converted if necessary)
    replacement
        Value to replace with (called each time if a function)

REFINEMENTS:
    /all
        Replace all occurrences
    /case
        Case-sensitive replacement
    /tail
        Return target after the last replacement position
