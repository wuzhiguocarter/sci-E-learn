TAC(1)                                                  User Commands                                                 TAC(1)



NAME
       tac - concatenate and print files in reverse

SYNOPSIS
       tac [OPTION]... [FILE]...

DESCRIPTION
       Write each FILE to standard output, last line first.  With no FILE, or when FILE is -, read standard input.

       Mandatory arguments to long options are mandatory for short options too.

       -b, --before
              attach the separator before instead of after

       -r, --regex
              interpret the separator as a regular expression

       -s, --separator=STRING
              use STRING as the separator instead of newline

       --help display this help and exit

       --version
              output version information and exit

AUTHOR
       Written by Jay Lepreau and David MacKenzie.

REPORTING BUGS
       Report tac bugs to bug-coreutils@gnu.org
       GNU coreutils home page: <http://www.gnu.org/software/coreutils/>
       General help using GNU software: <http://www.gnu.org/gethelp/>
       Report tac translation bugs to <http://translationproject.org/team/>

COPYRIGHT
       Copyright   ©   2013   Free   Software   Foundation,   Inc.    License   GPLv3+:   GNU   GPL   version   3  or  later
       <http://gnu.org/licenses/gpl.html>.
       This is free software: you are free to change and redistribute it.  There is NO WARRANTY, to the extent permitted  by
       law.

SEE ALSO
       rev(1)

       The  full  documentation  for  tac  is  maintained  as  a  Texinfo manual.  If the info and tac programs are properly
       installed at your site, the command

              info coreutils 'tac invocation'

       should give you access to the complete manual.



GNU coreutils 8.21                                       March 2016                                                   TAC(1)
