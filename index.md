Basic Things

     * Display gdb version information (show-version.md)
     * Display gdb copyright related information (show-copying-warranty.md)
     * No prompt message is displayed at startup (start-gdb-silently.md)
     * No prompt message is displayed when exiting (quit-gdb-silently.md)
     The output will not be paused when there is a lot of output information.

Function

     List function names
     Whether to enter a function with debugging information
     Entering a function without debugging information
     Exit the function being debugged
     Execute function directly
     Print function stack frame information
     Print tail call stack frame information
     Select function stack frame
     Toggle function stack frame up or down

Breakpoint

     Set breakpoints in anonymous space
     Break point at program address
     Break point at program entry
     Breakpoint on file line number
     Save the breakpoints that have been set
     Set temporary breakpoint
     Set conditional breakpoint
     Ignore breakpoints

Observation Point

     Set observation point
     Setting observation points only takes effect for specific threads
     Set read watchpoint
     Set read and write watchpoints

Catchpoint

     Let the catchpoint only trigger once
     Set catchpoint for fork call
     Set catchpoint for vfork call
     Set catchpoint for exec call
     Set catchpoint for system calls
     Cracking anti-debugging programs by setting catchpoints for ptrace calls

Print

     Print ASCII and wide character strings
     Print the contents of an STL container
     Print the contents of a large array
     Print the value of any consecutive element in the array
     Print the index subscript of an array
     Formatted print array
     Print the value of a function local variable
     Print process memory information
     Print the value of a static variable
     Print the type and file of the variable
     Print memory value
     Print source code lines
     Print one structure member per line
     Print objects by derived type
     Specify the input and output devices of the program
     Using "$\_" and "$\__" variables
     Print information about dynamically allocated memory by the program
     Print the value of the variable in the call stack frame

Multiple processes/threads

     Debugging an already running process
     Debug child process
     Debugging parent and child processes simultaneously
     View thread information
     Print stack information of all threads
     Use the maintenance command to view thread information on Solaris
     Do not display thread startup and exit information
     Only allow one thread to run
     Using the "$_thread" variable
     Debugging multiple programs simultaneously in one gdb session
     Print program process space information
     Using the "$_exitcode" variable

Core Dump File

     Generate core dump files for debugging processes
     Load executable program and core dump file

Compilation

     Set assembly instruction format
     Break point at the first assembly instruction of the function
     Automatically disassemble the code to be executed later
     Map source program and assembly instructions
     Display the assembly instructions to be executed
     Print register value
     Display program original machine code

Change Program Execution

     Change the value of a string
     Set the value of a variable
     Modify the value of PC register
     Jump to the specified location for execution
     Using breakpoint commands to change the execution of a program
     Modify the binary file of the debugged program

Signal

     View signal processing information
     Whether to pause the program when a signal occurs
     Whether to print signal information when a signal occurs
     Whether to throw the signal to the program for processing when the signal occurs
     Send a signal to the program
     Using the "$_siginfo" variable

Shared Library

     Display shared link library information

Script

     Configure gdb init file
     How to parse script files
     Save command history

Source File

     Set source file search path
     Replace the directory where source files are found

Graphical Interface

     Enter and exit the graphical debugging interface
     Show assembly code window
     Show register window
     Resize window

Other

     Format of command line options
     Support preprocessor macro information
     Keep unused types
     Use the abbreviated form of a command
     Execute shell commands and make in gdb
     Execute cd and pwd commands in gdb
     Set up command prompt
     Set the parameters of the program being debugged
     Set the environment variables of the debugged program
     Get help information for a command
     Record the process of executing gdb
     Print C++ virtual table and its contents
