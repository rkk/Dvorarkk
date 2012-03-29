# Dvorarkk - Dvorak for programmers
The Dvorak keyboard layout has been around for long, reducing
the friction of typing, over Qwerty and the like. Without
kickstarting the Dvorak/Qwerty flame war, I'll just note that
I've been a happy Dvorak customer for more than a decade.  

Dvorak and Qwerty were designed for typists, entering
large amounts of natural language data having high frequency
of alphanumerics (a-Z, 0-9) over symbols (#$^*, etc). Thus,
the numeric top row (1-0) provides numerics first, and symbols
second, if the user presses Shift.


## Programmers vs. typists
But, I'm a programmer not a typist. I enter large amounts
of programming language data, with a significantly
higher symbol frequency, as mandated by the programming
language syntax. PHP is probably the worst case for this,
as variables are prefixed with "$", statements
end with ";" , functions need parenthesis pairs both in definition
and usage. The Unix terminal is just as bad.  

In the end, I spend more time with my Shift key than
with my kids.


## Symbols over numerics
My solution is simple, swap the numeric row contents, providing
symbols first, and numerics second, if the user presses Shift.  

Normal Dvorak:

    Numeric row:            1234567890
    Numeric row with shift: !@#$%^&*()

Dvorarkk:

    Numeric row:            !@#$%^&*()
    Numeric row with shift: 1234567890


## Supported platforms
Layout files are provided for Mac OS X and X11 (Linux, *BSD, etc).  
In Mac OS X, the layout was created using Ukelele, and is tested
on Mac OS X 10.6.8.  
In X11, a standard US Dvorak xmodmap mapping file was updated
and is tested on Ubuntu Linux 10.04.


## But...
Your coworkers probably hate using your computer because you
use Dvorak. They'll hate you even more if you use Dvorarkk ;)