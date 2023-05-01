

XSS POLYGLOT - all in one test
https://github.com/0xsobky/HackVault/wiki/Unleashing-an-Ultimate-XSS-Polyglot 

other payloads

try to bypass the restrictions such as tag removal, encoding or character blacklisting.

# Where usually to test for xss? - Any user input area

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




