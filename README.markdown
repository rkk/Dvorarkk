# Dvorarkk - Dvorak for programmers

    NORMAL           SHIFT           SECOND LEVEL (ALT)
    ~!@#$%;&*(){}    ~1234567890[]   §!@#$%^&*()[]
    :,.pyfgcrl/=     "<>PYFGCRL?+    æβ…pyfgcrl/≠
    aoeuidhtns-|     AOEUIDHTNS_\    åøéüiðhþnß-| 
    `'qjkxbmwwvz     <`QJKXBMWVZ    >'öjkxbmwvz

The Dvorak keyboard layout has been around for long, reducing
the friction of typing, over Qwerty and the like. Without
kickstarting the Dvorak/Qwerty flame war, I'll just note that
I've been a happy Dvorak customer for more than two decades.

Dvorak and Qwerty were designed for typists, entering
large amounts of natural language data having a higher frequency
of alphanumerics (a-Z, 0-9) over symbols (#$^*, etc). Thus,
the numeric top row (1-0) provides numerics first, and symbols
second, if the user presses Shift.

But I'm a programmer, not a typist. I enter large amounts
of programming language data, with a significantly
higher symbol frequency, as mandated by the programming
language syntax. PHP and Perl are probably the worst case for this,
as variables are prefixed with "$", statements
end with ";" , functions need parenthesis pairs both in definition
and usage. The Unix terminal is just as bad, and don't get
me started on Lisp.

In the end, I spend more time with my Shift key than
with my kids.

Thus, the Dvorarkk layout was created.


## Improvements

  - Provide symbols rather than numerics on the number row
  - Make Vi and shell-friendly symbols such as `:` and `|` on accessible keys, e.g near Tab and Enter
  - Support national characters such as æ, ø and ð on the second level using Alt
  - Remap right Shift to Alt, to accommodate second level characters


## Installation
Copy the layout by cloning this repository to somewhere in the local
filesystem,

    git clone https://github.com/rkk/Dvorarkk.git ~/.config/dvorarkk

Load the layout into the current X11 session,

    xmodmap ~/.config/dvorarkk/X11/dvorarkk.xmodmap

For the true UNIX legacy experience and maximum value for money,
remap CapsLock to Control,

    setxkbmap -option ctrl:nocaps
    xmodmap ~/.config/dvorarkk/X11/dvorarkk.xmodmap

Please note that setxkbmap resets the layout to default US, so run
xmodmap _after_ setxkbmap.
If you want a permanent installation, call these commands from your
window manager or X11 session configuration files.


## Supported platforms
Layout files are provided for X11, and tested on Debian-based Linux
distributions and to some degree, OpenBSD and NetBSD.

Mac OS X and Windows are _not_ supported, although older versions of
layout files for these platforms are available in the Unsupported
directory. Use these at your own risk.


# But...
Your coworkers probably hate using your computer because you
use Dvorak. They'll hate you even more if you use Dvorarkk.
