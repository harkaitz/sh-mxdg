# SH-MXDG

## Help

mxdg

    Usage: mxdg 
    
    Configure *xdg-open(1)* assigning programs to certain files and
    URLs. All the information is stored in [~/.config/mimeapps.list]
    [~/.local/share/applications].
    
        -v                     : Show configuration.
        -an APP[=CMD] [-X] ... : Create new application.
            -C COMMENT  -I ICON    -M MIME 
            -G CATEGORY -O OPT=VAL -K KEYWORD
        -al                    : List applications.
        -ad APP                : Delete application.
        -ul                    : List assignations.
        -un URI[=APP]          : Assign URIs to application.
        -ud URI                : Delete URI assignation.             
    
    For example: mxdg -an firefox -X -un http -un https ...

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

