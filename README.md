# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:

### Ip2location:
<img width="1920" height="1200" alt="Screenshot 2026-08-06 085937" src="https://github.com/user-attachments/assets/113d3324-3cb3-4242-9e82-58f3987be29c" />

This image shows the geolocation details of the IP address. The server is located in France, specifically in Paris. It also indicates the use of a data center and DDoS protection service.



### web.archive.org :
<img width="1920" height="1140" alt="Screenshot 2026-08-06 200802" src="https://github.com/user-attachments/assets/ffce9465-0bab-4a0f-83d3-e61813a88e49" />

This shows archived records of the website from the Wayback Machine. It displays how many times the site was saved and the types of files captured. Most of the content is in HTML format, indicating regular web pages.

## Webserver Finger Printing:
### Ping :
<img width="1600" height="869" alt="WhatsApp Image 2026-08-06 at 9 25 11 AM" src="https://github.com/user-attachments/assets/bbaac635-bf1c-4a59-b43a-b7450148cf66" />


This shows the ping results to the domain from a Kali Linux terminal. It confirms that the server is active and responding to requests. The response times vary, showing network latency between systems.



### Nmap :
<img width="1600" height="869" alt="WhatsApp Image 2026-08-06 at 9 25 11 AM (1)" src="https://github.com/user-attachments/assets/17c86891-f7f1-4562-a1fb-b391867aaa43" />


This is an Nmap network scan performed on the domain education gouv.fr using a Kali Linux terminal. The output lists several open ports, including 21 (FTP), 22 (SSH), and standard web ports like 80 and 443, indicating the services currently reachable on that server.

### Whatweb :
<img width="1600" height="869" alt="WhatsApp Image 2026-08-06 at 9 25 12 AM" src="https://github.com/user-attachments/assets/5038d0c9-192e-4031-8e13-a13ec212886f" />


This image shows the output of the WhatWeb tool, which identifies the various technologies powering the website education gouv.fr. It reveals that the site uses the Bitrix Site Manager CMS, runs on an nginx web server, and includes components like jQuery and Google Tag Manager.

## Tracing the Location

### TCP Traceroute:

<img width="1622" height="853" alt="Screenshot 2026-08-24 103245" src="https://github.com/user-attachments/assets/9dcafc36-4b57-4637-9239-d5b086ea4d9e" />


The information gathering techniques tools/procedure were identified successfully
