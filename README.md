# scanweb-application

This script will prompt you for the URL of the web application to scan. The web application will then be scanned for vulnerabilities using the nmap command with the -sV and --script vuln options. The -sV option tells nmap to perform a version scan, which will identify the web application's version and other software running on the server. The --script vuln option tells nmap to run a set of vulnerability scripts against the web application.

### Here are some additional notes about the script:

#### The nmap command is used to scan for vulnerabilities.
#### The -sV option is used to perform a version scan.
#### The --script vuln option is used to run a set of vulnerability scripts.
#### The read command is used to get input from the user.
#### The echo command is used to display messages to the user.
