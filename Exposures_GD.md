MANUAL: 
Good doks for finding exposures manual tests on target website 
site:*.domain.com = for subdomains 

then remove www using - operator
remove most common subdomains to be left with this like this 

site:*.domain.com -www -blog -mail -support -help -chat 

this will find 
1. unique subdomains 
2. domains with unique urls 
3. domains with "information cannot be shown" or previewed. 

TIP: the more results you see that needs to be excluded in dorks the more likely you are to get any low hanging fruits or misconfigured digital assets, exposures, etc. 
