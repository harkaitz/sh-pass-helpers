# PASS HELPERS

Utilities writter around *pass(1)* for comfort. It uses *dmenu(1)*
and *xclip(1)*.

## Help

pass-del

    Usage: pass-del ACCOUNT ...

pass-dmenu

    Usage: pass-dmenu
    
    Fast password accessing tool.
    
    (1) If the clipboard contains an URL, displays an account list
        and stores the selected account. The username is stored in
        the clipboard.
    (2) If the clipboard contains an account, types the password.
    
    Usage example:
    
    (1) Select an URL, and CTRL-C.
    (2) CTRL-P to execute "pass-dmenu".
    (3) Click in "username" and type CTRL-V.
    (4) Click in "password" and type CTRP-P to execute "pass-dmenu".

pass-gen

    Usage: pass-gen : Generate 3 new passwords.

pass-ls

    Usage: pass-ls : List passwords.

pass-x

    Usage: pass-x
    
    Select an account and print password.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
