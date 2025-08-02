# Specialized-Search-Engines-tryhackme
Learn to efficiently search the Internet and use specialized search engines and technical docs.

You are familiar with Internet search engines; however, how much are you familiar with specialized search engines? By that, we refer to search engines used to find specific types of results.

# Shodan
Let’s start with Shodan, a search engine for devices connected to the Internet. It allows you to search for specific types and versions of servers, networking equipment, industrial control systems, and IoT devices. You may want to see how many servers are still running Apache 2.4.1 and the distribution across countries. To find the answer, we can search for apache 2.4.1, which will return the list of servers with the string “apache 2.4.1” in their headers.

https://www.shodan.io/

Consider visiting Shodan Search Query Examples for more examples. Furthermore, you can check Shodan trends for historical insights if you have a subscription.

https://www.shodan.io/search/examples

https://trends.shodan.io/

# Censys
At first glance, Censys appears similar to Shodan. However, Shodan focuses on Internet-connected devices and systems, such as servers, routers, webcams, and IoT devices. Censys, on the other hand, focuses on Internet-connected hosts, websites, certificates, and other Internet assets. Some of its use cases include enumerating domains in use, auditing open ports and services, and discovering rogue assets within a network. You might want to check Censys Introductory Use Cases.

https://search.censys.io/

https://docs.censys.com/docs/ls-introductory-use-cases#/

# VirusTotal
VirusTotal is an online website that provides a virus-scanning service for files using multiple antivirus engines. It allows users to upload files or provide URLs to scan them against numerous antivirus engines and website scanners in a single operation. They can even input file hashes to check the results of previously uploaded files.

The screenshot below shows the result of checking the submitted file against 67 antivirus engines. Furthermore, one can check the community's comments for more insights. Occasionally, a file might be flagged as a virus or a Trojan; however, this might not be accurate for various reasons, and that's when community members can provide a more in-depth explanation.

https://www.virustotal.com/gui/home/upload
