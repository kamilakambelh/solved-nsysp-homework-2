Download Link: https://assignmentchef.com/product/solved-nsysp-homework-2
<br>
<h1>Part 1</h1>

<ol>

 <li>Edit the parse.c file to use <em>strtok()</em> and <em>realloc( )</em> to implement the <em>parse()</em> and <em>free_argv()</em></li>

</ol>

functions.

<ol start="2">

 <li>Files provided: shell.h shell.c parse.c</li>

 <li>Example:</li>

</ol>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/03/734.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/03/734.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>

<h1>Part 2</h1>

<ol>

 <li>Add code to the builtin.c stub to recognize the echo, quit, exit, logout and bye commands. Write functions implementing these commands, and add a new line for</li>

</ol>

each command to table inbuilts[] just above the line {NULL, NULL}.

<ol start="2">

 <li>File provided:</li>

</ol>

Builtin.c

<ol start="3">

 <li>echo example:</li>

</ol>

echo print all strings echo -n N: print the specified string




<ol start="4">

 <li>quit example: exit, quit, logout and bye terminate the program.</li>

</ol>







<h1>Part 3</h1>

<ol>

 <li>Edit the run_command.c file so a child process is created to run the command, and the parent waits for the child process to terminate. Check for builtin commands first, create a new process only for commands which are not built in. Use the parser from pervious labs to create from the command line the argv array passed to the child.</li>

</ol>

Hint: You can use <em>exec()</em>/<em>execvp()</em> function, <em>waitpid()</em> function and the <em>fork()</em> system call.

<ol start="2">

 <li>File provided: run_command.c 3. Example:</li>

</ol>







<h1>Part 4</h1>

<ol>

 <li>Edit the is_background.c file to detect an “<strong>&amp;</strong>”. Alter the run_command.c file so that if a task is running in the background, the parent does not wait. Do not worry about</li>

</ol>

background processes becoming zombies at this point; this will be addressed later.

<ol start="2">

 <li>File provided: is_background.c 3. Example:</li>

</ol>


