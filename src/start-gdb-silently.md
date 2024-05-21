# No prompt message is displayed at startup

When we start GDB, it prints some information at the beginning itself, and then displays the prompt.

For example:

	$ gdb
	GNU gdb (GDB) 7.7.50.20140228-cvs
	Copyright (C) 2014 Free Software Foundation, Inc.
	License GPLv3+: GNU GPL version 3 or later <http://gnu.org/licenses/gpl.html>
	This is free software: you are free to change and redistribute it.
	There is NO WARRANTY, to the extent permitted by law.  Type "show copying"
	and "show warranty" for details.
	This GDB was configured as "x86_64-unknown-linux-gnu".
	Type "show configuration" for configuration details.
	For bug reporting instructions, please see:
	<http://www.gnu.org/software/gdb/bugs/>.
	Find the GDB manual and other documentation resources online at:
	<http://www.gnu.org/software/gdb/documentation/>.

 	For help, type "help".
	Type "apropos word" to search for commands related to "word".
	(gdb)

 If you don't want this information displayed when you start GDB, just start gdb with -q option:

 	$ gdb -q
	(gdb)

You can also create an alias in .bashrc file so that you don't have to type -q everytime you start GDB:

	alias gdb='gdb -q'
