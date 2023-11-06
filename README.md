# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

# Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

# site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/31bed98f-7e41-4bb3-8707-ece17dca3eab)

# filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/1789ba62-e92f-4032-8436-d0d44263903e)



# intext:
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/1fc31619-2558-4dc5-a89d-c1e91676bde2)


# inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/6bf4161b-514d-49f7-9efd-70864124546c)

# intitle: 
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/f3903f21-89f9-4528-94ae-79ff2b7b0a2f)

# link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/ad0c68d8-edc2-44ca-836c-4d9d4df145ff)

# cache:
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/e97d7027-04ca-499c-b6c4-b64b6da16222)

 
# DNS Enumeration

## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/fcb6caf5-5a87-4f19-8835-b48d9bfdb363)



## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/d9d40acd-9799-4545-94b5-c39dccc08b8c)
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/a84c1a32-cf82-4ee9-9022-c5190c41fa10)


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/e7f24d19-503a-4cf0-b8f6-5291001e6516)
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
# ![image](https://github.com/Roselineb/Enumeration/assets/128909895/61937572-c34b-43f0-a79c-59361ef847f8)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
