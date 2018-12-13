# Whois-info
Bash Script to find website's thick whois web address and query it for information


Usage:

whois-info 
or
whois-info website.com
can also now accept email addresses & websites i.e.

whois-info user@testemail.com

whois-info https://github.com/JReming85/Whois-info/

as it will strip it down to the domain testemail.com or github.com

It will then retrieve a thin whois record on that domain and extract the Registrar's WHOIS Server. It will then retrieve a thick whois record from the Registrar containing all the websites registration information and display in line with all the extra data getting trimmed.

After it displays the whois record it will then retrieve the mail servers address
