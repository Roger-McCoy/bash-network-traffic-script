# bash-network-traffic-script
 A Linux Bash script (search_script) that separates a large, month-long network log file (NetworkTraffic.log) into smaller, separate log files for each day (May1.log, May2.log, etc...), and then searches through the file for suspicious traffic while logging the occurrences into an output file (SearchTotals.log).
 
 Built in Linux shell with Bash. 
 
 Features:
* For loop to increment through daily log files.
* Use of grep utility and associated command-line options.
* Use of echo utility and associated command-line options to achieve readability.
* Output redirection.
