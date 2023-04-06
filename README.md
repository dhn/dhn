# Excerpt of vulnerabilities I found in the last years

Over the past years I’ve found several vulnerabilities on several products/vendors for example, HP, ASUS, BioStar, Telekom, Adobe, Siemens, GDATA, Avast, Comodo, Synology, Wacom and many more. These list is just a short list because not all vulnerabilities have got an CVE number:

## 2018

* **HP Network Automation**:
  - [CVE-2018-6492](https://softwaresupport.softwaregrp.com/document/-/facetsearch/document/KM03158014) - Cross-Site Scripting (XSS)
  - [CVE-2018-6493](https://softwaresupport.softwaregrp.com/document/-/facetsearch/document/KM03158014) - SQL Injection
  
* **SeedDMS**:
  - [CVE-2018-12939](https://nvd.nist.gov/vuln/detail/CVE-2018-12939) - Directory Traversal
  - [CVE-2018-12940](https://nvd.nist.gov/vuln/detail/CVE-2018-12940) - Unrestricted File Upload
  - [CVE-2018-12941](https://nvd.nist.gov/vuln/detail/CVE-2018-12941) - Remote Code Execution
  - [CVE-2018-12942](https://nvd.nist.gov/vuln/detail/CVE-2018-12942) - SQL Injection
  - [CVE-2018-12943](https://nvd.nist.gov/vuln/detail/CVE-2018-12943) - Cross-Site Scripting (XSS)
  - [CVE-2018-12944](https://nvd.nist.gov/vuln/detail/CVE-2018-12944) - Persistent Cross-Site Scripting (XSS)  
 
## 2019 
  
* **SITOS Six**:
  - [CVE-2019-15746](https://nvd.nist.gov/vuln/detail/CVE-2019-15746) - Command Injection
  - [CVE-2019-15747](https://nvd.nist.gov/vuln/detail/CVE-2019-15747) - Privilege Escalation
  - [CVE-2019-15748](https://nvd.nist.gov/vuln/detail/CVE-2019-15748) - Authorization Bypass
  - [CVE-2019-15749](https://nvd.nist.gov/vuln/detail/CVE-2019-15749) - Account Takeover 
  - [CVE-2019-15750](https://nvd.nist.gov/vuln/detail/CVE-2019-15750) - Cross-Site-Scripting (XSS)
  - [CVE-2019-15751](https://nvd.nist.gov/vuln/detail/CVE-2019-15751) - Unrestricted File Upload
 
* **HiDrive Desktop Client**:
  - [CVE-2019-9486](/2019-04/hidrive-local-privilege-escalation-via-insecure-wcf-endpoint/) - Local Privilege Escalation (LPE)

* **ASUS Aura Sync**:
  - [CVE-2019-17603](/2020-06/asus-aura-sync-stack-based-buffer-overflow/) - Local Privilege Escalation (LPE)

## 2021

* **Synology DSM**:
  - Local Privilege Escalation (LPE) vulnerability that I’ve found in Synology DSM <= 6.2.4-25554 back in 2021. This vulnerability has no **CVE**, no advisory and was not mention in any update. At least an [acknowledgement](https://www.synology.com/en-global/security/bounty_program/acknowledgement) on their page `¯\_(ツ)_/¯`.

## 2022

* **Adobe Acrobat Reader DC**:
  - [CVE-2022-34226](https://www.zerodayinitiative.com/advisories/ZDI-22-994/) - Out-Of-Bounds Read

## 2023

* **Siemens Tecnomatix Plant Simulation**:
  - [CVE-2023-27401](https://www.zerodayinitiative.com/advisories/ZDI-23-328/) - Out-Of-Bounds Read
  - [CVE-2023-27402](https://www.zerodayinitiative.com/advisories/ZDI-23-327/) - Out-Of-Bounds Read
  - [CVE-2023-27403](https://www.zerodayinitiative.com/advisories/ZDI-23-332/) - Out-Of-Bounds Read
  - [CVE-2023-27405](https://www.zerodayinitiative.com/advisories/ZDI-23-331/) - Out-Of-Bounds Read
  - [CVE-2023-27399](https://www.zerodayinitiative.com/advisories/ZDI-23-322/) - Out-Of-Bounds Write
  - [CVE-2023-27404](https://www.zerodayinitiative.com/advisories/ZDI-23-330/) - Stack-based Buffer Overflow

* **GDATA Total Security**:
   - [CVE-2023-27347](https://www.zerodayinitiative.com/advisories/ZDI-23-379/) - Local Privilege Escalation (LPE)

PS: This idea is shameless stolen from my colleague [frycos](https://github.com/Frycos/Frycos) 😄.
