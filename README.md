<img src="assets/header.svg" width="100%" alt="Shreesh Kallihal. Security engineer in Dublin. Detection, incident response and Python automation.">

<p align="center">
  <a href="https://whyyoushouldhireme.netlify.app"><b>Why you should hire me</b></a> &nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/shreeshk"><b>LinkedIn</b></a> &nbsp;|&nbsp;
  <a href="https://medium.com/@shreeshk08"><b>Blog</b></a> &nbsp;|&nbsp;
  <a href="https://zenodo.org/records/18216717"><b>Research paper</b></a> &nbsp;|&nbsp;
  <a href="https://huggingface.co/spaces/shreeshk08/NIDS"><b>Live demo</b></a>
</p>

## Hello

I am a security engineer in Dublin with an MSc in Cybersecurity (1:1 Honours) from National College of Ireland and nearly 2 years of hands-on security work on AWS at a US startup.

My work has three habits. I investigate an alert until I know the root cause. I write Python so the same manual task never has to be done twice. I test my own builds the way an attacker would, then fix what I find and write it up in plain language.

<img src="assets/stats.svg" width="100%" alt="About 2 years of security operations on AWS, 100+ TryHackMe rooms, 10+ security articles, 1 peer reviewed paper, 99.87 percent intrusion detection accuracy, 2 vulnerabilities responsibly disclosed.">

## Featured work

| Project | What it does | Proof |
| --- | --- | --- |
| **Automated Phishing Email Triage System** (MSc practicum) | A 6 stage Python pipeline with a 22 rule detection engine, SPF, DKIM and DMARC checks and TheHive and Cortex ready output. Precision rose from 0.50 to 0.85 at about 35 ms per email, tested against a live URLhaus feed of 78,000+ indicators with 79 unit tests. | Python, around 80 percent test coverage |
| **Network Intrusion Detection System** | XGBoost reached 99.87 percent accuracy on CICIDS2017, ahead of an MLP (96.68) and a 1D-CNN (89.10). SHAP explanations show analysts why a flow was flagged. | [Try it on Hugging Face](https://huggingface.co/spaces/shreeshk08/NIDS) |
| **BOND: AI Security Assistant** | A production security chatbot on Google Gemini with 2 layers of prompt injection defence, a server side API key, rate limiting and input sanitisation. | [shamrocksecurity.me](https://shamrocksecurity.me) |
| **AWS Cloud Security Hardening and Penetration Testing** | A production equivalent Amazon EC2 build with 40+ controls aligned to OWASP, NIST CSF and CIS benchmarks, then a penetration test with 6 tools and 12 rated findings. The final build had zero critical CVEs. | Nmap, Nessus, Nikto, WPScan, SSLScan, Wireshark |
| **Java and Web Application Security Audit** | Found, exploited and fixed 5 vulnerabilities in a Java 21 and MySQL 8 application, each mapped to OWASP Top 10:2025 with a CWE reference. Also found 5 classes of flaw in the BodgeIt Store with ZAP and SonarQube. | [Java audit](https://medium.com/@shreeshk08/i-was-given-a-broken-java-app-i-found-every-flaw-proved-every-attack-then-fixed-everything-7079c433e28e), [web audit](https://medium.com/@shreeshk08/someone-left-this-web-app-wide-open-i-walked-right-in-4cdc2bd446ba) |
| **Python Network Enumerator** | Runs Nmap reconnaissance in one pass: live host discovery, port scanning, service and version detection and OS fingerprinting, with JSON, TXT and HTML reports. | Python, Kali Linux |
| **Responsible disclosure** | Reported 2 vulnerabilities to their owners: a broken authorisation check (IDOR) on a careers website and a prompt injection weakness in a hosted LLM playground. | Find, reproduce, report |

## Experience

**Software Engineer I, Security Focus, Smiota Labs** (Sept 2023 to Aug 2025)

- Investigated alerts from endpoint, network and cloud logs in Microsoft Sentinel with KQL, and tuned detection rules until false positives stayed below 4 percent on live production traffic.
- Wrote a Python threat hunting script over AWS CloudTrail logins that surfaced 3 account compromise attempts in its first month.
- Built Python incident response automation that isolates affected AWS resources, revokes sessions and sends notifications. Mean time to respond fell by around 35 percent.
- Ran Nessus and Nmap scans across the Amazon EC2 estate, triaged findings by CVSS score and tracked remediation against SLAs.
- Replaced a 40 minute manual report each shift with a scheduled script that runs in under 2 minutes.
- Collected evidence for 2 audits, ISO 27001 and PCI DSS, and mentored 5 new hires.

**Full Stack Developer Intern, Saunshi Softwares** (Oct 2022 to Dec 2022)

- Built and deployed a web application with 4 security controls designed in from the start: input validation, parameterised queries, authenticated session management and OWASP Top 10 mitigations.

## Toolbox

| Area | Tools and skills |
| --- | --- |
| Security operations | Microsoft Sentinel, KQL, Splunk, alert triage, incident response, threat hunting, detection rule tuning, MITRE ATT&CK |
| Vulnerability and application security | Nessus, Nmap, Burp Suite, ZAP, SonarQube, Nikto, WPScan, Wireshark, OWASP Top 10, CVSS, CWE |
| Cloud and identity | AWS (EC2, IAM, S3, CloudTrail), MFA, least privilege, CIS benchmarks, Azure (working knowledge) |
| Code and automation | Python, Java, Bash, PowerShell, SQL, JavaScript, REST APIs, Git, unit testing, CI/CD |
| Governance and risk | ISO 27001, PCI DSS, NIST CSF, GDPR, audit evidence, third party risk assessments |
| AI in security | XGBoost, SHAP, LLM security, prompt injection defence, Google Gemini API |

## Education

- **MSc Cybersecurity, 1:1 Honours**, National College of Ireland, Dublin (Sept 2025 to Sept 2026). Class Representative and Student Council Member.
- **BE Computer Science**, Visvesvaraya Technology University (June 2019 to June 2023).

## Certifications and training

| Area | Certificate | Issued by |
| --- | --- | --- |
| Security certifications | Certified Threat Intelligence and Governance Analyst (CTIGA), Jan 2026 | Red Team Leaders |
| | Certified Network Security Practitioner (CNSP), Dec 2025 | The SecOps Group |
| | CompTIA Security+ (in progress) | CompTIA |
| | Vulnerability Management Detection and Response | Qualys |
| | Threat Modeling Certified Derisker | IriusRisk |
| | ISC2 Candidate | ISC2 |
| Security training | Security Operations (SOC) Training, Jan 2026 | Microsoft |
| | Advent of Cyber, 24 cyber challenges, Dec 2025 | TryHackMe |
| | Cyber Threat Management | Cisco |
| | Introduction to Cybersecurity | Cisco |
| | Cybersecurity Foundations | Project Management Institute |
| | Cybersecurity Awareness | NASBA |
| | Ethical Hacking Masterclass | Nikistian Media |
| | Security Learning Plan | AWS Academy |
| Cloud and AI | AWS Academy Graduate, Cloud Foundations | Amazon Web Services |
| | Oracle Cloud Infrastructure AI Foundations Associate | Oracle |
| | Career Essentials in Generative AI | Microsoft and LinkedIn |
| Job simulations | Cybersecurity Analyst Job Simulation | Tata Group, Forage |
| | Cyber Security Management Job Simulation | ANZ Australia, Forage |
| | Cybersecurity Simulation | JPMorgan Chase, Forage |
| | Cybersecurity Simulation | Mastercard, Forage |
| Software development | Web Development Bootcamp | Udemy |
| | Java and C# Programming Languages | Liberty Security System |
| | JavaScript Programming Bootcamp | Open Weaver |
| | HTML and CSS Online Bootcamp | Open Weaver |
| Other | Teams Foundations: Project Management | Project Management Institute |
| | Sustainability Badge (ethics, governance, AI and data governance), Dec 2025 | National College of Ireland |

## Blog

I write on **[Medium](https://medium.com/@shreeshk08)**: 10+ CTF walkthroughs and security articles that explain technical findings in plain language. Two to start with:

- **[I was given a broken Java app. I found every flaw, proved every attack, then fixed everything.](https://medium.com/@shreeshk08/i-was-given-a-broken-java-app-i-found-every-flaw-proved-every-attack-then-fixed-everything-7079c433e28e)** A full security audit of a Java 21 and MySQL 8 application, from exploit to fix.
- **[Someone left this web app wide open. I walked right in.](https://medium.com/@shreeshk08/someone-left-this-web-app-wide-open-i-walked-right-in-4cdc2bd446ba)** Five classes of flaw in the BodgeIt Store, found with ZAP and SonarQube.

## Research

- **[Network Architecture of the Banking Sector](https://zenodo.org/records/18216717)**, peer reviewed paper (Zenodo, 2025).

## Recognition

- **Rashtrapati Puraskar (2017)**, India's highest youth honour, presented by the President of India through Bharat Scouts and Guides after 6 years of national level service.
- **IEEE Student Member** who organised cybersecurity workshops for fellow students.
- 100+ TryHackMe rooms and HackTheBox machines across Linux, Active Directory and the web.
- Speaks English, Kannada and Hindi.

## Say hello

The fastest way to reach me is [LinkedIn](https://www.linkedin.com/in/shreeshk). The longer story is at [whyyoushouldhireme.netlify.app](https://whyyoushouldhireme.netlify.app).

<img src="assets/footer.svg" width="100%" alt="">
