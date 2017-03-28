USAGE:
     TO-INTEGER value /unsigned

DESCRIPTION:
     Synonym of TO INTEGER! when used without refinements, adds /UNSIGNED.
     TO-INTEGER is a function .

RETURNS:
    (undocumented)

ARGUMENTS:
    value [integer! decimal! percent! money! char! time! issue! binary! any-string!]

REFINEMENTS:
    /unsigned
        For BINARY! interpret as unsigned, otherwise error if signed.
