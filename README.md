# Cve-2020-5029-finder
It is  a small script to fetch out the  subdomains/ip vulnerable to CVE-2020-5902 written in bash. 

# Affected Version
In BIG-IP versions 15.0.0-15.1.0.3, 14.1.0-14.1.2.5, 13.1.0-13.1.3.3, 12.1.0-12.1.5.1, and 11.6.1-11.6.5.1, the Traffic Management User Interface (TMUI), also referred to as the Configuration utility, has a Remote Code Execution (RCE) vulnerability in undisclosed pages.
  
# Usage
In order to use this you need to install httporbe installed

#confuration
first list out the subdomains in a list.txt (with http/https) you can use httporbe for this
	 
	 cat list.txt | httprobe | tee -a domains (here the ip/domains will store as http or https://xx.xx.xx.xx)

	 ./cve-checker.sh /user/path_to_filtered_domians



![Test Image 1](https://github.com/GovindPalakkal/Cve-2020-5029-finder/blob/master/Screen%20Shot%202020-07-08%20at%204.54.59%20PM.png)
