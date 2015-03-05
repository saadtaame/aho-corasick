# aho-corasick
A C++ implementation of the AhoCorasick pattern matching algorithm.
### How to use ###
<pre>
next_id = 0;
AhoCorasick ac(patterns); // patterns is a string vector
ac.match(text); // text is the string to search in
</pre>

The function match needs to be customized to application (print matches?, count matches?, etc..).
