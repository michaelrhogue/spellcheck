# Spell Checker submitted by Michael Hogue
This program, written in bash, uses binary sort to find words in a large dictionary file - from the function findword.  This function is pretty good, but there was a problem with the hyphen recursion that was attempted.  The idea was to split hypenated words into multiple single words

The checkProperName and suggest functions are extremely under-developed, and probably don't provide the most useful information.

At the end of the main loop there is a grep command that prints out the requested line numbers and surrounding text.

Thanks!

Michael