# Solution

**C**

You can set which level of logging messages you want the **logging.Logger** instance your are using to display. In this case, we want to control it with an environment variable so end-users only see
info and above (warning, error and critical) and if needed we can set the environment variable to *DEBUG* in order to see all log messages while debugging our code.
