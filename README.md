# How to read man pages

View the [source text here](https://www.dca.fee.unicamp.br/sysadmin/helpstuff/faq/man-reading.html#:~:text=Sections,fork%20in%20section%201.).

## Sections
The man pages are divided into sections, here's a brief describtion of each:
Section 1  User commands
Section 2  System calls
Section 3  Library calls
Section 4  Devices, special files
Section 5  File formats
Section 6  Games
Section 7  Miscellaneous
Section 8  Administrative commands

Some commands occur in more than one section. When refering to a man page, the section is shown in paranthesis after the command to help you find the man page.
  For example, the `chmod` C function is referred to as chmod(2), as the man page of the `chmod` user command is referred to as chmod(1).

Since man pages with the same name can occur in different sections, you may need to specify the section when using the man command. For instance, to get the C function chmod, you would need to say "man 2 chmod", otherwise you'd always get the chmod in section 1. The man command will search all sections (not in order but usually starting with 1) until it finds a match, so if you wanted the man page for fork(2), you could just say "man fork", since there is no fork in section 1.
