Havij
-----
Version 1.12 Free
Advanced SQL Injection Tool
Copyright © 2009-2010
By r3dm0v3


Contact
-------
WebSite: http://ITSecTeam.com
Forum:   http://Forum.ITSecTeam.com
Email:   Info@ITSecTeam.com


Licence
-------
The free version of Havij is free software. We hope it be useful for you.
This software is provided "as is" without warranties.
Feel free to share and distribute it anywhere but please keep the files original!

There is a commerical version of Havij that is not free.
To purchase Pro version of Havij please visit http://itsecteam.com


Disclaimer
----------
We are NOT responsible for any damage or illegal actions caused by the use of this program. Use on your own risk!


What's New?
-----------
In this version major features and changes have been done and many bugs were fixed.
-HTTPS Support
-MsSQL Blind added
-MsAccess Blind added (Commerical version only)
-PostgreSQL added (Commerical version only)
-Check for update added.
-Manual queries with result added. (Commerical version only)
-1 row per 1 request (all in one request) added (Commerical version only)
-Dumping data into file added (Commerical version only)
-Saving data in XML format added (Commerical version only)
-Injecting targets with any port added (default http port is 80) (Commerical version only)
-XSS bug in saved reports fixed.
-Clear log added.
-Apply button added to the settings so it is possible to change the settings anytime (Commerical version only)
-keyword test and correction method added.
-finding columns count and string column optimized for better injection and data base detecting.
-Finding columns count and string column made better.
-"414 Request-URI too long" bug fixed.
-New method for getting tables and columns in mssql added.
-Some bugs in MsAccess injection when syntax has been defined manually fixed.
-Enable XP_Exec added to cmdshell (Commerical version only)
-Enable OS_Ex added to cmdshell (Commerical version only)
-Enable remote desktop added to cmdshell (Commerical version only)
-Confusing MsSQL 2005 with MySQL when finding columns count fixed.
-Broken MD5 cracker sites removed.
-a bug in detecting mssql no error fixed.
-a bug in getting columns in mssql no error fixed.
-a bug in injecting into access database fixed.
-a bug in getting data in mssql fixed.
-a bug in finding mssql's row count fixed.
-a bug in detecting database type when column count is found fixed.
-a bug in MsSQL no error manual syntax and command executation fixed.


Features
--------
1.  Supported Databases with injection methods:
       a. MsSQL 2000/2005 with error
       b. MsSQL 2000/2005 no error union based
       c. MsSQL Blind (Commerical version only)
       d. MySQL union based
       e. MySQL Blind
       f. MySQL error based
       g. Oracle union based
       h. PostgreSQL union based (Commerical version only)
       i. MsAccess union based
       j. MsAccess Blind (Commerical version only)
2.  HTTPS Support (Commerical version only)
3.  Proxy support
4.  Automatic database detection
5.  Automatic type detection (string or integer)
6.  Automatic keyword detection (finding difference between the positive and negative response)
7.  Trying different injection syntaxes
8.  Options for replacing space by /**/,+,... against IDS or filters
9.  Avoid using strings (magic_quotes similar filters bypass)
10. Manual injection syntax support
11. Manual queries with result (Commerical version only)
12. Bypassing illegal union
13. Full customizable http headers (like referer,user agent and ...)
14. Load cookie from site for authentication
15. Real time result
16. Guessing tables and columns in mysql<5 (also in blind) and MsAccess
17. Fast getting tables and columns for mysql
18. Getting one row in one request (all in one request) (Commerical version only)
19. Dumping data into file (Commerical version only)
20. Saving data as XML format (Commerical version only)
21. View every injection request sent by program (Commerical version only)
22. Enabling xp_cmdshell and remote desktop (Commerical version only)
23. Multi thread Admin page finder
24. Multi thread Online MD5 cracker
25. Getting DBMS Informations
26. Getting tables, columns and data
27. Command executation (mssql only)
28. Reading system files (mysql only)
29. insert/update/delete data


How to use
----------
This tool is for exploiting SQL Injection bugs in web application.
For using this tool you should know a little about SQL Injections.
Enter target url and select http method then click Analyze.
Note: Try to url be valid input that returns a normal page not a 404 or error page.


Version History
---------------
Version 1.12 2010/08/30
-Check for update added.
-Some bugs in MsAccess injection when syntax has been defined manually fixed.
-Enable XP_Exec added to cmdshell.
-Enable OS_Ex added to cmdshell.
-Enable remote desktop added to cmdshell.
-Result added to manuall queries.
-PostgreSQL database added.
-Confusing MsSQL 2005 with MySQL when finding columns count fixed.
-Broken MD5 cracker sites removed.

Version 1.11 Not Released
-a bug in detecting mssql no error fixed.
-a bug in getting columns in mssql no error fixed.
-finding columns count and string column optimized for better injection and data base detecting.
-Finding columns count and string column made better.
-XSS bug in saved reports fixed.
-a bug in injecting into access database fixed.
-keyword test and correction method added.
-MsSQL Blind added.
-Clear log added.
-a bug in getting data in mssql fixed.
-Apply button added to the settings so it is possible to change the settings anytime.
-new method for getting tables and columns in mssql added.
-"414 Request-URI too long" bug fixed.
-MsAccess Blind added.
-Injecting targets with any port (default http port is 80).
-Https added.
-a bug in finding mssql's row count fixed.
-a bug in detecting database type when column count is found fixed.
-a bug in MsSQL no error manual syntax and command executation fixed.
-'All in one request' feature added.
-Dump into File added.
-Save data as XML format added.

Version 1.10 2010/05/25
-Runtime error on canceling analyze fixed.
-Bug in finding mssql's database when COLLATE is not supported fixed.
-A bug in getting mssql tables fixed.
-Html encoding bug when saving data fixed.
-A bug in automatic string type detection fixed.
-Borken sites in md5 cracker fixed, a new site added.
-Tables and Columns list improved.
-A few other changes.

Version 1.09 2010/05/06
-Software's window made resizeable.
-Adding and removing nodes to tables tree view list enabled by right click.
-All data bases will be shown in the tree view list.
-Start row in data extraction can be changed now.
-A bug in bypassing illegal union when getting tables and columns in mysql fixed.
-Saving and loading current injection job enabled.
-Start column added to settings
-Blind injection character set added to settings
-MsSQL injection syntax changed.
-Tables and columns brute forcing in mysql 4 blind added.
-Better injection in mssql
-Get data made better in mysql injection
-Find keyword works better now
-Mysql detection from error added.
-A bug in getting current db in mysql fixed.
-Positive pattern replaced with keyword.
-Manual keyword specification.
-Tables and Columns list improved.

Version 1.08 2010/02/13
-MySQL Blind Injection added.
-Auto injection type detection added.
-Try different injection syntaxes becase an option.
-Following redirections became an option.
-Admin list, Table list and Column list improved.

Version 1.07 2009/12/08
-finding column count and string column in mssql no error when type was string fixed.
-some bugs in analyze method for mysql fixed.
-manual syntax available for mysql and mssql no error
-Online MD5 cracker added.

Version 1.06 2009/10/09
-finding string column in mysql made better.
-oracle added.
-bug in find admin when file list was huge (oveflow error!) fixed.
-bug in delete/update/insert when database was not default fixed.
-retry bug in find admin fixed.
-'load cookie' added to settings.

Version 1.05 Not Released
-proxy added.
-find admin added.
-filter made available for mssql
-a bug fixed (blind detection when target is not vulnerable and injection type is string)
-MsAccess database added
-finding columns count and string column in mysql made better.

Version 1.04 Not Released
-filter added to get data
-data list changed
-updating data enabled
-delete row added
-insert new row added
-group_concat added.
-bug in guessing columns in mysql fixed.
-bug with null strings when 'avoid using strings' was on fixed.
-bug in getting data in mysql when type is string fixed.
-injection method changed for mysql.
-bug in guessing tables and columns in mysql<5 fixed.
-program displays injection syntax after analyze.
-'user agent' added to settings.

Version 1.03 2009/08/19
-bug in getting info fixed when collate not allowed in mssql
-analyzing method changed for mysql data bases.
-finding db server made better.
-injection with different syntaxes added.
-query added.
-data base server detection is now both automated and user selective.
-injection of string type for double quotation mark added.
-bugs in cmdshell fixed.
-command executation enabled for mssql no error.
-some little bugs fixed.

Version 1.02 2009/08/08
-access privilege detection added when getting data
-string type added.
-an error in getting http response code fixed.
-a bug in finding columns fixed.
-command executation added.
-'do not find column count in mssql with error' added to settings.
-html encode bug in mssql with error fixed.
-another try for finding columns count added.
-logging made better.
-redirect added.
-guessing tables and columns in MySQL<5 added.
-a bug in getting tables fixed.
-some other little changes.

Version 1.01 2009/07/25
-post method added.
-program finds count of tables or columns before getting tables and columns.
-'Replace space with' added to the settings.
-'Additional http headers' added to the settings.
-positive pattern checking algorithm made better.
-stop on erros added.
-a second method added for finding DB server type.
-mssql no error data base added.
-new look (command buttons changed into menus)
-a little problem in getting mysql's tables data was fixed.
-save option added.
-a bug in data base 'mssql with error' when getting tables and columns with 'avoid using strings' option fixed.
-some other little changes.

Version 1.0 beta 2009/07/04
-Initial release
