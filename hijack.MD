USAGE:
     HIJACK victim hijacker 

DESCRIPTION:
     Cause all existing references to a function to invoke another function.
     HIJACK is a function .

RETURNS: [function! blank!]
    Proxy for the original function, BLANK! if hijacked with BLANK!

ARGUMENTS:
    victim [function! any-word! any-path!]
        Function value whose references are to be affected.
    hijacker [function! any-word! any-path! blank!]
        The function to run in its place or BLANK! to extract prior code.
