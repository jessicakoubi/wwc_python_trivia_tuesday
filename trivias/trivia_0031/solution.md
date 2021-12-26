# Solution

**D**

You can use the **thefuzz** library (previously named **fuzzywussy**) to do string matching using the Levenshtein distance equation. The *extractOne* method 
will find the single best match above a score for a given string in a list or dictionary of choices. You can set the *score_cutoff* argument to only return 
the best match if its score is above that number.