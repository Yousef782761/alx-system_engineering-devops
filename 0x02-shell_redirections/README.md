scripts
The special charachter (/) prevents the next character from being interpreted as a special character to make the output in a required shape
 The command cat diplays the content of the file /etc/passwd
3- The script cat /etc/passwd /etc/hosts concatenate both the output of /etc/passwd and /etc/hosts which will display some information about the device like usernamaes and ID\'s amd also the mappings of the hostnames to ip addresses
The command tail outputs the content by default the last 10 line in a file but the number of lines the wished to be displayed can be adjusted
The command head by default prints the first 10 lines inside a file which is here /etc/passwd
The command sed -n \'3p\' modifies the text to get the only line required to be printet or displayed
