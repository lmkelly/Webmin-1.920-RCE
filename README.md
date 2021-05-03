## Webmin 1.920 RCE

### [CVE-2019-15107](https://www.cvedetails.com/cve/CVE-2019-15107/)

The purpose of this repository is to provision a vulnerable web application running Webmin 1.920, and to document the steps one would take to exploit it and gain remote code execution. This extremely severe vulnerability has since been patched by webmin, additional details regarding the CVE can be found [here](https://www.cvedetails.com/cve/CVE-2019-15107/).

This exploit takes advantage of a command injection vulnerability within the password_change.cgi file of Webmin version 1.890 through 1.920. While this backdoor is no longer present in the default installations, before being discovered the backdoor had been worked into all sourceforge downloads of the package. The ansible scripts above install all of the required packages and create a vulnerable webmin 1.920 webserver on an ubuntu machine. 

#### Head over to the [Wiki](https://github.com/lmkelly/Webmin-1.920-RCE/wiki) for more detailed build instructions.
