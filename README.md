# Taiwo Abubakar

I work where engineering, cybersecurity, and compliance meet. By day I am an Engineering Project Manager at Con Edison in New York. I run ModNet projects for electrical substations and transmission lines, check design work against local, state, and federal rules, and see projects through from inception to closeout. Before that I worked in cybersecurity at MNCPPC, where most of my work was identity audits and automation.

My resume name is Araf Abubakar. This page is the short version of what I do, what I know, and where to see the work itself.

## What I do

* **Identity and access governance.** At MNCPPC I audited Active Directory and Azure AD and found 200+ stale or over-privileged accounts, then helped build a remediation plan covering 3,000+ users.
* **Security automation.** I wrote PowerShell audits for MFA coverage and password policy that cut the manual review workload by 70%.
* **GRC.** Control tracking, access reviews, and framework mapping across NIST CSF 2.0, ISO 27001:2022, NIST SP 800-53, and SOC 2. I also write post-incident reviews of the kind a board or an auditor would read.
* **Regulated project delivery.** At Con Edison I oversee substation and transmission design packages, coordinate government agencies, contractors, and the public, and verify technical contracts, equipment procurement, and change orders.
* **Building.** I still write code, mostly Python, PowerShell, and JavaScript, for checkers, audit tools, and small utilities like the ones in this portfolio.

## Start here

These four show the range of what I do best:

* [Project BLACKSWAN](https://github.com/tearbu/project-blackswan): a full GRC investigation and post-incident review of the October 2022 BNB Chain bridge exploit. Report, risk register, control gap matrix, framework crosswalk, remediation roadmap, audit plan, and board briefing.
* [Project BLACKSWAN II](https://github.com/tearbu/project-blackswan-ii): the same treatment for the October 2026 Binance exchange hack, written as an interim assessment while the facts are still settling.
* [Identity and Access Audit Toolkit](https://github.com/tearbu/identity-access-audit-toolkit): PowerShell audits for stale accounts, MFA coverage, and privileged groups, with a demo mode that runs on sample data.
* [Daily Vuln Lab](https://github.com/tearbu/daily-vuln-lab): every day I pick the most significant new vulnerability surfacing on Hacker News and build a small lab on it, a checker, a detection rule, or an analysis. First edition covered CVE-2026-119618, the Apache mod_http2 RCE. Latest edition, 22 November, covers Upload2Shell, CVE-2026-125396, a Ghostscript sandbox bypass reachable through uploads, print jobs, and email attachments.

## Portfolio by area

### Governance, risk, and compliance

* [ccm-access-governance](https://github.com/tearbu/ccm-access-governance): continuous controls monitoring checker, 7 controls mapped to ISO 27001:2022 and SOC 2, run against fictional data with 2 passing and 5 failing. The newest control, AG-07, checks that every service account has a named owner and a review in the last 90 days.
* [grc-control-tracker](https://github.com/tearbu/grc-control-tracker): ISO 27001:2022 control status, evidence gaps, and overdue reviews.
* [ai-governance-risk-assessment](https://github.com/tearbu/ai-governance-risk-assessment): NIST AI RMF tiering for AI use cases, with gaps per system.
* [ransomware-readiness-assessment](https://github.com/tearbu/ransomware-readiness-assessment): maturity scoring with critical gaps called out plainly.

### Identity and access

* [access-review-toolkit](https://github.com/tearbu/access-review-toolkit): flags orphaned accounts, dormant access, and segregation of duties conflicts.
* [cloud-iam-policy-analyzer](https://github.com/tearbu/cloud-iam-policy-analyzer): reviews cloud IAM policies for over-broad permissions.
* [sso-saml-implementation-toolkit](https://github.com/tearbu/sso-saml-implementation-toolkit): SAML metadata validation with a go or no-go verdict.
* [scim-provisioning-simulator](https://github.com/tearbu/scim-provisioning-simulator): shows what breaks when deprovisioning fails, including orphaned leaver accounts.

### Detection and security operations

* [security-log-triage](https://github.com/tearbu/security-log-triage): sorts raw security logs into what needs attention first.
* [siem-detection-rules](https://github.com/tearbu/siem-detection-rules): detection rules with a test harness and sample events.
* [incident-response-tracker](https://github.com/tearbu/incident-response-tracker): incident tracking in Python with SQLite.
* [phishing-header-analyzer](https://github.com/tearbu/phishing-header-analyzer): reads email headers for signs of spoofing and phishing.
* [vuln-report-analyzer](https://github.com/tearbu/vuln-report-analyzer): turns scanner output into a prioritized remediation plan.
* [linux-hardening-audit](https://github.com/tearbu/linux-hardening-audit): Bash checks against common Linux hardening settings.

### Cloud and AI security

* [serverless-call-analytics](https://github.com/tearbu/serverless-call-analytics): serverless pipeline that analyzes support call transcripts, with S3, Lambda, DynamoDB, and API Gateway defined in a SAM template. It classifies issues, scores sentiment and urgency, and redacts card numbers and SSNs before storage. Verified locally on 7 fictional transcripts with 22 automated tests passing. Not yet deployed to a live AWS account.
* [cloud-security-posture-scanner](https://github.com/tearbu/cloud-security-posture-scanner): posture checks across cloud resources with scored findings.
* [kubernetes-security-audit](https://github.com/tearbu/kubernetes-security-audit): workload checks for risky Kubernetes settings.
* [web-security-posture-checker](https://github.com/tearbu/web-security-posture-checker): scores HTTP security headers and cookie flags.
* [llm-prompt-injection-tester](https://github.com/tearbu/llm-prompt-injection-tester): an offline test harness for prompt injection, based on the OWASP LLM risks.

Every project here runs on fictional sample data and includes the real output of a demo run in its README, so you can see what the tool actually does without setting anything up.

## Skills

**Security tools:** Splunk, Wireshark, Nessus, Qualys, Packet Tracer, Zscaler, SIEM, AWS GuardDuty, CrowdStrike, Burp Suite, Snort, Autopsy, FTK, EnCase

**Systems:** Linux, Active Directory, Entra ID, Windows Server, Azure AD, Microsoft 365, AWS, Azure

**Languages and scripting:** Python, PowerShell, Bash, SQL, JavaScript, TypeScript, Node.js, HTML, CSS

**Core strengths:** GRC, Incident Response, Threat Hunting, Vulnerability Analysis, Malware Analysis, Network Security, Cloud Security, Application Security, Project Management, Data Visualization

## Certifications

**Completed:** ISO/IEC 27001:2022, Azure Data Science Associate, Asana Workflow

**In progress:** CompTIA Security+, CompTIA Network+, CompTIA CySA+, AWS Certified Security Specialty, AWS Certified Solutions Architect

## Background

* Engineering Project Manager, Con Edison, New York, Sep 2026 to present
* Cybersecurity Analyst Intern II and Full Stack Developer Intern II, MNCPPC, Largo, MD, Jan to Aug 2025
* Technical Lead, Geo Prime Energy, Michigan, Jun to Aug 2024. Led a 30-person team and a website redesign that cut vulnerability findings by 40%.
* Full Stack Developer, Gomycode, Lagos, Jan to Jun 2023
* Lead Supervisor Engineer, Shelat Engineering, Lagos, Jan to Dec 2022. Ran 50+ projects and supervised 40 people.

**Education:** MS in Management Information Systems, Bowie State University (2025). Bachelor of Engineering in Mechanical Engineering, Kwara State University, Nigeria (2021).

## Current focus

Security engineering, GRC, and identity and access governance. The daily vuln lab above is the current habit: read what just broke, work out how you would catch it, build the small thing that proves it, publish it. The newest build is the serverless call analytics pipeline, built to be deployed to a live AWS account next.

## Contact

LinkedIn: [linkedin.com/in/arafabubakar](https://www.linkedin.com/in/arafabubakar)

If you are hiring for security, GRC, or identity work, the projects above are the fastest way to see how I think and what I can build.
