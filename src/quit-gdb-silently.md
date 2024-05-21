# Do not ask for any prompt while quiting/exiting while being attached to any process

GDB prompts when exiting when in an active debugging session, being attached to a process.

	(gdb) quit
	A debugging session is active.

        Inferior 1 [process 3982973] will be killed.

    Quit anyway? (y or n) n

If you do not want this prompt to be displayed/asked, you can use the following in the GDB prompt to disable it.

	(gdb) set confirm off

 Alternatively, if you want this for all your future sessions, you can mention this command/instruction in the .gdbinit file which you place in the root of your home directory:

 	# cat ~/.gdbinit
 	set confirm off

This way, everytime when GDB starts, it will read the instruction from .gdbinit file, and apply to its session.
