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
![266200042-65a81eda-1543-4761-bf5a-b1e22783d89b](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/8c0f7188-0883-456d-9d9c-067cfdd2184f)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## Output:
![266200206-f3a3f77c-2e80-4b1a-9f4d-ae99e42a5e5e](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/74d41ba4-4738-4884-9a2b-10b447653fd5)

## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:
![266200285-b3ed46a4-61fb-4086-baed-fc10cbcf57ad](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/855ed0a4-e12a-40fb-95e0-9cd3eb71176c)

## History of the website:
## Output:
![266200356-9a7580f3-84d2-4150-a07a-7dd12cfb77f2](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/bf74ef14-88dd-4670-a59a-8cfe4d57dec9)

## Webserver Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![266200488-96afee79-3b7a-4f34-85eb-f68f51716e15](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/f6343de2-7311-49fe-9b0a-335fa95e9201)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![266200562-a94781d7-73dd-4c7b-b161-2d3db08b461c](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/ac162e63-a8ec-427d-a58d-9b705e18d18e)

## Whatweb:
```
whatweb infosys.com
```
whatweb zoho.com
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![266200782-88a7f64b-0329-413a-a6a3-3603b9a6d0a9](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/f5b0230e-2fbf-4f24-81b9-e2fe5d019255)

![266200795-18eaa01f-70e3-4397-bfe9-183cdbd27186](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/9c6faed9-8195-4216-878e-adf47dc19318)


## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
##![266200930-ee29150f-c068-429a-9e8f-4aafb8d8272e](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/fe2649cf-0a11-4d82-b9ad-d8e807d586f9)
 Output:

## Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![266201037-2768c966-a25f-4ef1-91b7-fff9dd9c3271](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/350921e0-b3e7-41ea-add5-162f124c3421)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![266201126-5adb9206-3226-46cf-b630-c6fee4ded328](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/7370cf35-ab13-486a-9271-86f635052da9)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![266201200-fb2632fa-b607-4b5b-815b-d3d147b52331](https://github.com/KRISHNARAJ-D/InformationGathering/assets/119559695/39671e36-5b46-49ff-a118-15c6d50c60f3)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
