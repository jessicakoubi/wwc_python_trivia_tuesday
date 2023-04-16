# Solution

**A**

getpass.getuser() checks the environment variables LOGNAME, USER, LNAME and USERNAME, in order, and returns the value of the first one which is set to a non-empty string. This function should be preferred over os.getlogin().
