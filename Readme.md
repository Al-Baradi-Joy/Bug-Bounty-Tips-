1- site:*.target.com ext:php
2- echo sub.target.com | waybckurls | grep "\?" | uro | httpx -silent > parameters.txt 
3- nuclei -l parameters.txt -t fuzzing-templates
4- You may find xss,sqli,ssrf,open-redirect vulnerabilities 
