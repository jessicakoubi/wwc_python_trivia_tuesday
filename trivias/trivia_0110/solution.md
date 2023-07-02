# Solution

**B**

With subprocess, you can create pipes to communicate between the parent and child processes. A pipe is a unidirectional communication channel that connects one process's standard output to another's standard input.
You can create a pipe using the subprocess.Popen class with the stdout or stdin argument set to subprocess.PIPE.
