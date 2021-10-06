# Solution

**A**

The **subprocess.check_output()** function run a command with arguments and return its output in bytes. If the command return code is non-zero it will
raise the  *CalledProcessError* exception and have the return code in the *returncode* attribute and the output error in the *output* attribute.