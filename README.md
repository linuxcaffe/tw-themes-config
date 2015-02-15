# taskwarrior themes
_16color and 256color, light and dark theme files for taskwarrior_

This is a set of alternate themes for taskwarrior (http://taskwarrior.org).
They designed to be optimally readable, and they are different from the current default set in two important ways:
- they attempt to assign only a forground _or_ a background color to each element, allowing combinations that mean something.
- They use a completely different order-of-precedence (embedded in each theme) which means the colors are applied in a completely different sequence, than the default set. 

To try them out, download (clone) them to a local directory, and include one of them (at a time) in your .taskrc file. I keep mine in ~/.task/themes/

<pre>
# example:
include ~/.task/themes/dark-256.theme
</pre>
