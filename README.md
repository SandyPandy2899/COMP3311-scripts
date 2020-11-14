# COMP3311 scripts
---
copy scripts into your assignment folder before use
---
### update\_expected
1. creates ./tests/ directory (clears the directory if it exists)
2. scrapes "https://cgi.cse.unsw.edu.au/~cs3311/20T3/assignments/ass3/examples.php"
3. creates .sh files in tests/ dir for each command run
4. creates .exp files in tests/ dir for output of each comand
### run\_tests
1. runs each .sh file in tests/ and outputs to corresponding .out file
2. diffs corresponding .out and .exp
3. prints record of tests
