SQLBuilder
==========
(JDBC SPECIFIC)

This is a code snippet for a project currently being worked on with 4 other colleagues. It relies on JDBC and existing
code, so it wont run, I am merely displaying a solution for a problem explaiend below

Problem:
--------
We are concerned with SQLInjections from user Input so we used preparedStatements, although prepared Statements need
all SQL values to be inturn replaced by a '?'. This is explained in the Class. The overhead of doing this everytime
a sql query is called is un-neccessary, especially if you multiply that by un-necessary work being done by 4 other people.

Solution
--------
This class automatically replaces all values with question mark, and then sets the values iteratively when needed.


I hope this makes sense to people who know JDBC or atleast the solution does :)
