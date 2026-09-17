# Week 2 - Footprinting and Reconnaissance

Cybersecurity Internship project (Network Walks) - passive and active reconnaissance performed against the target domain networkwalks.com, with due permission.

Tools used:
* whois - Looked up domain registration and ownership details
* whatweb - fingerprinted the web technologies running on the site
* nslookup - resolved the domain to its IP address
* curl -I - pulled up the HTTP response headers
* wafw00f - checked for a Web Application Firewall
* dnsrecon - enumerates DNS records (name servers, MX, TXT, etc.)
* theHarvester - gathered emails, subdomains, and hosts related to the domain from public sources
* Maltego - ran a "To Email address {From whois}" transform on the domain entity found a email info@networkwalks.com (WHOIS privacy via network walks proxy)

## Google Hacking Database (GHDB) Dorks

Separate footprinting exercise using advanced Google search operators to identify publicly exposed resources.

*Task 1 - Found 10 live exposed security camera links using GHDB dorks, recorded with link, relevant dork and any exposed credentials.
*Task 2 - Found open directory listings containing downloadable mathematics PDF ebooks using the dork 'intitle:index.of "parent directory" mathematics pdf' recorded in the same table format.
