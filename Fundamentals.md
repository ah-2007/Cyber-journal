# Cybersec Fundamentals

## ~CIA Traid

### Overview
The CIA Triad is the foundation of cybersecurity. It consists of three principles: Confidentiality, Integrity, and Availability.

### Key Concepts
- Confidentiality → Protecting data from unauthorized access
- Integrity → Ensuring data is not modified
- Availability → Ensuring systems are accessible

### Important Terms
- Encryption → Protects confidentiality
- Hashing → Helps maintain integrity

### What I Learned
- Every security system is based on these three principles 
- If one fails, security is weak



## ~Information Gathering
### Overview
Information Gathering (also known as Reconnaissance) is the first phase of cybersecurity assessments and penetration testing.
It involves collecting data about a target system, network, or organization before attempting any exploitation.

### Key Concepts
#### Types of info gathering
- Technical - Uses tools, scripts, and technologies to gather data
- -> EG:- scanning websites, analyzing headers
- NON-Technical(OSINT) - Uses publicly available information
- -> EG:- social media, public records, company websites

#### Methods of Reconnaissance
- Active Reconnaissance - Direct interaction with the target
- -> EG:- scanning a website or server (Can be detected by the target)
- Passive Reconnaissance - No direct interaction with the target, Uses third-party sources
- -> EG:- WHOIS lookup, search engines

#### Google Dorking
- Advanced search techniques using Google
- Helps find: Hidden pages, Exposed files, Subdomains
- -> EG:- site:example.com filetype:pdf

#### HSTS (HTTP Strict Transport Security)
- A security mechanism that forces browsers to use HTTPS only
- Prevents downgrade attacks (HTTPS → HTTP)
- Ensures secure communication between user and server

#### Sitemap
- A file that lists the structure of a website
- Helps search engines understand and index content efficiently
- Usually found at: /sitemap.xml

#### Robots.txt
- Controls what search engines are allowed to index
- Located at: example.com/robots.txt
- Can reveal: Hidden directories, Restricted paths
- (Important: It does NOT secure content, it only gives instructions to crawlers)

### Tools
 [who is domail tools](https://whois.domaintools.com/)-
- Retrieves domain registration details
- Info like owner (if not hidden), registrar, dates
  
 [wappalyzer](https://www.wappalyzer.com/)-
- Browser extension
- Detects technologies used (frontend, backend, frameworks)
  
 [BuiltWith](https://builtwith.com/)-
- More detailed tech analysis of websites
- Shows hosting, CMS, analytics tools, etc.

 ### What I Learned
- Information gathering is the first step before any attack or pentest
- Both active and passive methods are used depending on the situation
- Tools help identify: Technologies used, Potential entry points
- HSTS improves security and can be checked during assessments
- robots.txt can unintentionally expose sensitive directories
- Domain registration info can sometimes be hidden using privacy protection
- More technologies = larger attack surface (more chances for vulnerabilities)


## ~TCP/IP
### TCP/IP is the core communication protocol used for internet networking. It defines how data is transmitted between devices.
- ➡️ See: [Networking](Networking.md)


## ~Linux
### Linux is a widely used operating system in cybersecurity for its flexibility and control over system processes.
- ➡️ See: [Linux](Linux.md)
