# SQL-Hierarchy-project
This project consists of SQL code that:
-Builds a hierarchy with a list of folder paths.
-Evaluates branch dates and assign newer/older ones to parent nodes.

It was ran on a database of 11 million rows which has to be done in 2 sets so the ram usage would not be exceeded.

The development consists of 2 steps. First, identifying branches and hierarchy levels out of the folder path. Secondly, a loop that
evaluates all the values on a hierarchy level at a time and assigns to the upper level the resulting values.
