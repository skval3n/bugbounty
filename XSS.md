

XSS POLYGLOT - all in one test
https://github.com/0xsobky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot 

other payloads

try to bypass the restrictions such as tag removal, encoding or character blacklisting.

# Types of XSS 

| By Priority| 
| ------------- |
| Stored | 
| Reflected | 
| DOM | 

# Where can be found ? 

| By type of context e.g., code/ urls| 
| ------------- |
| HTML attributes: When user input is improperly sanitized and used as an attribute value in HTML tags, an attacker can inject malicious scripts that execute when the attribute is triggered, like an “onclick” or “onmouseover” event.| 
| JavaScript: When user input is directly inserted into JavaScript code, it can lead to XSS vulnerabilities. For example, an attacker could exploit a vulnerable script that uses user input as part of a “document.write()” function. | 
| URL parameters: If user input is not properly sanitized before being used in URL parameters, attackers can inject malicious scripts that execute when the URL is loaded. | 

# Where to test for xss? - Any user input area

| Examples| 
| ------------- |
| comment sections| 
| search forms| 
| parameteres in the urls where you have x="value" test on value| 

# Identify indexable user input areas via Google Dorks

| Examples query for site:*.domain.com| 
| ------------- |
| "leave a comment" -sign in or with sign in| 
| "search" OR "find" -www| 

# Identify indexable user input areas via scripts / automation

| Examples of tools for automatic assessment of xss| 
| ------------- |
| TBD| 


# XSS specific to software / CVE

| Software known to allow xss | 
| ------------- |
| TBD| 

# Escalate XSS further to:

| Other attacks e.g.,| 
| ------------- |
|RCE https://www.bugcrowd.com/blog/the-ultimate-guide-to-finding-and-escalating-xss-bugs/  | 
| STEAL SESSION TOKENS| 
| BYPASS SOP (SAME ORIGIN POLICY)| 
| OPEN REDIRECT| 




