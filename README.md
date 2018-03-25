# libraryblorg
A new site to journal my librarian goals

<!-- vim regex to format marc and rda tables for posts.

:%s/\n/ | /g
that matches all new lines and replaces them with pipes


:s/| \(\d\d\d\)/|^M | \1/g 
where there is a pipe and 3 digits, inserts a newline and pipe
: is enter into command mode
s is to start a substitute expression like find and replace
/ is beginning first of 2 sections, begins the find
looks for a pipe (|) a space and a capture group of 3 digits \(\d\d\d\)
/ closes the find and starts next group
|^M | is a pipe, line break, and pipe--separating table elements
\1 is the capture group
/g is the end of the capture group, apply globally to the line
-->

<!-- tags:
book-zine
3d-obj
digital
living
-->

