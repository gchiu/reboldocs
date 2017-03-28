USAGE:
     REWORD source values /case /escape delimiters /into output

DESCRIPTION:
     Make a string or binary based on a template and substitution values.
     REWORD is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    source [any-string! binary!]
        Template series with escape sequences
    values [map! object! block!]
        Keyword literals and value expressions

REFINEMENTS:
    /case
        Characters are case-sensitive
    /escape
        Choose your own escape char(s) or [prefix suffix] delimiters
    delimiters [blank! char! any-string! word! binary! block!]
        Default "$"
    /into
        Insert into a buffer instead (returns position after insert)
    output [any-string! binary!]
        The buffer series (modified)
