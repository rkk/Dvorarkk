# Dvorarkk - Dvorak for programmers
![Dvorarkk layout](/Documentation/dvorarkk.png)
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


## Improvements

  - Provide symbols rather than numerics on the number row
  - Make Vi and shell-friendly symbols such as `:` and `|` on accessible keys, e.g near Tab and Enter
  - Support national characters such as æ, ø and ð using Alt
  - Remap right Shift to Alt

For true UNIX legacy, remap CapsLock to Control.


## Supported platforms
Layout files are provided for Mac OS X and X11 (Linux, *BSD, etc).  
In Mac OS X, the layout was created using Ukelele. On X11, a standard
US Dvorak xmodmap mapping file was updated.  
Dvorarkk is tested on the following,

  - Mac OS X 10.6 to 10.10
  - Ubuntu Linux 10.04 to 17.04
  - OpenBSD 6.2


## But...
Your coworkers probably hate using your computer because you
use Dvorak. They'll hate you even more if you use Dvorarkk.
