"I/O" redirections known as Input/Output redirections
Outputs usually consist of the command resukts and the status and error message that tell us hoe th command is getting along.

Many commands print their output on the display but by using special notations we can redirect the output to and from files.
1.Standard input: We commonly know it as stdin but the shell recognizes it wit a file descriptor number 1. Commands accept input from here and by default its the keyboard. To redirect stdin froma file instead of the keyboard, the "<" operator is used.

2.Standard\ output: We commonly know it as stdout but the shell uses the file descriptor number 2 to identify it. Command line commands send their resukts here. We use the ">" redirection operator to redrect stdout to another file. ">" is used to append the file.

3.Standrad error: We commonly know it as stderr but the shell  identifies it using file descriptor number 3.

4.Pipelines: Connecting multiple commands together forms pipelines. They use the pipeline operator (|).
The difference betwenn the pipeline operator and the redirection operator is that the pipeline operator connects the output of one command with the input of the second command (command 1 | command 2) while a redirection operator connects a command with a file (command > file)

5.Filters: Commands used in a pipeline are referred to as filters. They take in stdin, perform an operation upon it and sends results to stdout.
~                                                                                                                                               
