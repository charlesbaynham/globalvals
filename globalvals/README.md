Global Vals (version 1.1)
=========================

URL: https://github.com/charlesbaynham/globalvals
(c) Charles Baynham 2019

License: LaTeX Project Public License 1.3c

This package allows the user to declare a variable which can then be used
anywhere else in a document, including before it was declared. This is done
by putting the definitions into the .aux files, therefore requiring two runs
to get it right.

It implements two commands: \defVal{<value>} and \useVal{<value>}. \defVal
sets up a global variable and \useVal recalls it.

Using \defVal twice will result in an error. Using \useVal for an undefined
value will output the text "??"



The package is released 'as is' with no warranty under the LaTeX Project Public
License, version 1.3c.
