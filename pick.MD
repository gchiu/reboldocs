USAGE:
     PICK aggregate index 

DESCRIPTION:
     Returns the value at the specified position.
     PICK is a function .

RETURNS: [<opt> any-value!]
    Picked value, or void if index not present

ARGUMENTS:
    aggregate [any-series! map! gob! pair! date! time! tuple! bitset! port! varargs!]
    index
        Index offset, symbol, or other value to use as index
