# capstone-research
The main idea of a penetration tester is to use scripts to test the vulnerabilities of a machine. Acting like a hacker or a red teamer for the benefit of a business. Kali Linux is a tool used by a tester for an audit. The threats captured by a test will be outdated and unpatched software. Tests can identify misconfigured security controls in firewalls, routers, and access control lists. There is also a whole area of testing called physical pen testing and social engineering but it won't be the focus of my study. In an unsecured application attackers can exploit vulnerabilities and gain unauthorized access, testers can find these exploits first. Since we will focus primarily on software and programming issues, what are they?  A software vulnerability could allow an attacker unwanted access to systems and files. Once an attacker is in they can steal data or add a system to a botnet among other possibilities. There are many ways to discover vulnerabilities but the most common would be to run a port scan after discovering the IP address of the target. The most commonly used and well-known tool is Nmap, which scans software collects information about running services, and determines if the target is subject to known vulnerabilities. The Next step would be to choose a method for exploiting they have to be aware of IDS and security intervening if they catch them. Here is a list of software vulnerabilities from Jfrog.com
  Buffer overflows: These allow someone to put more data into an input field than what the field is supposed to allow. An attacker can take advantage of this by placing malicious commands into the overflow portion of the data field, which would then execute.
  SQL Injection: This could allow an attacker to inject malicious commands into the database of a web application. The attacker can do this by entering specially-crafted Structured Query Language commands into either a data field of a web application form, or into the URL of the web application.  If the attack is successful, the unauthorized and unauthenticated attacker would be able to retrieve or manipulate data from the database.
  Third-party libraries: Many programmers use third-party code libraries, rather than try to write all software from scratch. This can be a real time-saver, but it can also be dangerous if the library has any vulnerabilities. Before using any of these libraries, developers need to verify that they don’t have vulnerabilities.
  Application Programming Interfaces: An API, which allows software programs to communicate with each other, could also introduce a software vulnerability. Many APIs are not set up with strict security policies, which could allow an unauthenticated attacker to gain entry into a system.
  Adhering to common parctices is a good way to mitigate vulnrabilites. With this being said nothing will make a system bulletproof. In the upcoming capstone project I can expect to run into challenges like IP adresses blocking scans which can be mitigated with an alternate scan. There will also be other blocks in my way that I will have to find work arounds for if that means alternate exploits or diffrent scripts to be ran.

  Capstone deployment infromation
In this next section I will provide a description of what i deployed and how. First I set up 2 machines. Kali Linux and metasploitable 2 from rapid7. This is a virtual machine that can be exploited. I will be choosing a few of the most common CVE's and demostrating how they work, how to exploit and how to mitigate.

 Link to DOCS
 https://docs.google.com/document/d/1Gtw5PDPjnXXxdiGrGaRQO7za4pd7BmFAnSab99vfD0g/edit?usp=sharing

 Link to presentation

 https://docs.google.com/presentation/d/10CzWJG5VXaZrJyWAutYmvDDa8kxHGoBCCEV7XMjVdCA/edit?usp=sharing

 Resources
 https://github.com/sendgrid/email-templates/blob/master/paste-templates/password-reset.html
https://github.com/criggs626/PhishingTemplates/blob/master/emails/microsoft.html
https://emkei.cz/
https://www.rapid7.com/db/modules/exploit/multi/samba/usermap_script/
