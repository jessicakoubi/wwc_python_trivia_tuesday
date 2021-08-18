# Solution

**B**

You can set the nargs parameter of the parser.add_argument() method to + to gather all the arguments in a list. But unlike using *, it will throw an error message if not at least one argument is provided.