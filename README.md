# SQL-Hierarchy-project
In the world of organizations and computers we can find several situations in which we have to deal with hierarchy data. The task usually consists of identifying the hierarchy, making operations and creating a visual representations of the nodes structure. If we deal with a high volumes of data we want to do this in a specially efficient way.

In this project I share code to make these 3 tasks with high volumes of data (11 million rows). SQL code to identify the hierarchy and make operations. Python code to create a representation of the biggest part of the tree possible.

The SQL process consists of 2 steps:
- First, identifying branches and hierarchy levels out of the folder path string.
- Secondly, a loop that evaluates all the values on a hierarchy level at a time and assigns to the upper level the calculated values (in this case max and min date values).
