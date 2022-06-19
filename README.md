<h3>Project name:</h3>
<h2> get-next-line</h2>

<b>Project description:</b>
 - This project make you learn a highly interesting new concept in C programming: static variables.

<b>A task:</b>
<p>• Repeated calls (e.g., using a loop) to your get_next_line() function should let you read the text file pointed to by the file descriptor, one line at a time.</p>
<p>• Your function should return the line that was read. If there is nothing else to read or if an error occurred, it should return NULL.</p>
<p>• Make sure that your function works as expected both when reading a file and when reading from the standard input.</p>
<p>• Please note that the returned line should include the terminating \n character, except if the end of file was reached and does not end with a \n character.</p>
<p>• Your header file get_next_line.h must at least contain the prototype of the get_next_line() function.</p>
<p>• Add all the helper functions you need in the get_next_line_utils.c file</p>
<p>• Because you will have to read files in get_next_line(), add this option to your compiler call: -D BUFFER_SIZE=n. It will define the buffer size for read(). The buffer size value will be modified by your peer-evaluators and the Moulinette in order to test your code.</p>
<p>• You will compile your code as follows (a buffer size of 42 is used as an example): cc -Wall -Wextra -Werror -D BUFFER_SIZE=42 <files>.c</p>
<p>• We consider that get_next_line() has an undefined behavior if the file pointed to by the file descriptor changed since the last call whereas read() didn’t reach the
end of file.</p>
<p>• We also consider that get_next_line() has an undefined behavior when reading a binary file. However, you can implement a logical way to handle this behavior if you want to.</p>
