CHECK_UTILS
===========
Simple C utilites that assist in safer code development.


USAGE
-----
These are very simple function definitions, and the easiest way to use them 
in code is simply to include them. 

For example: 

    #include <check_alloc.c> 

And then make sure to include the directory where the source code lives 
in the compilation (-I for gcc).

You can simply copy the respective files to your source code directory, and 
then pass the current directory to the compiler.  For example: 

    % gcc -I. ... 


AUTHOR
------
Cameron McBride
Sept 2012 
cameron.mcbride@gmail.com


