# Azure Security Collation
This repository is a collation of resources related to various components of Azure Security broken down into categories.

Table of Contents:
- [Azure Security Collation](#azure-security-collation)
  - [Service Security Grab-Bag](#service-security-grab-bag)
  - [Reference and Learning Content](#reference-and-learning-content)
    - [General Azure Security](#general-azure-security)
    - [Sentinel](#sentinel)
    - [Microsoft Defender for Cloud](#microsoft-defender-for-cloud)
    - [Identity](#identity)
    - [App/Dev](#appdev)
    - [Data, AI, and IoT](#data-ai-and-iot)
    - [Infrastructure](#infrastructure)
    - [Cryptography](#cryptography)
    - [Compliance](#compliance)
    - [Misc](#misc)
- [Contributing](#contributing)

## Service Security Grab Bag

- [Azure Services Security Grab Bag List](/security-grab-bag/README.md)

The grab bag pages are designed to be a quick reference of security considerations for the various Azure Services.

## Reference and Learning Content

### General Azure Security

- [Microsoft Security Documentation](https://docs.microsoft.com/en-us/security/)
- [Microsoft Security Technical Content Library](https://www.microsoft.com/en-us/security/content-library)
- [Azure Security Benchmark Documentation](https://docs.microsoft.com/en-us/security/benchmark/azure/)
- [Security Start Here - Architecture & Design](https://learn.microsoft.com/en-us/azure/architecture/guide/security/security-start-here)
- [End-to-End Security in Azure](https://docs.microsoft.com/en-us/azure/security/fundamentals/end-to-end)
- [Microsoft Security Best Practices  Security Compass)](https://docs.microsoft.com/en-us/security/compass/compass)
- [Security in the Microsoft Cloud Adoption Framework](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/secure/)
- [Azure Well Architected Framework - Security Pillar](https://docs.microsoft.com/en-us/azure/architecture/framework/security/overview)
- [Security rapid modernization plan](https://docs.microsoft.com/en-us/security/compass/security-rapid-modernization-plan)
- [Azure security best practices and patterns](https://docs.microsoft.com/en-us/azure/security/fundamentals/best-practices-and-patterns)
- [The Azure Security Architect Map](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/the-azure-security-architect-map/ba-p/714091)
- [Microsoft Cybersecurity Reference Architectures](https://docs.microsoft.com/en-us/security/cybersecurity-reference-architecture/mcra)
- [Azure Security top 10 best practices](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/secure/security-top-10)
- [Secure DevOps Kit for Azure](https://azsk.azurewebsites.net/)
- [Chief Information Security Officer (CISO) Workshop Training](https://docs.microsoft.com/en-us/security/ciso-workshop/ciso-workshop)
- [How Microsoft Implemented a Zero Trust Security Model](https://www.microsoft.com/en-us/insidetrack/implementing-a-zero-trust-security-model-at-microsoft)
- [Microsoft Security, Compliance and Identity Community](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/ct-p/MicrosoftSecurityandCompliance)
- [Microsoft Security Community Youtube](https://www.youtube.com/c/microsoftsecuritycommunity)
- [Optimizing Azure Monitor Log Analytics Costs](https://trstringer.com/log-analytics-expensive-part-1-discovery/)

### Sentinel

- [Microsoft Sentinel Academy](https://microsoft.github.io/PartnerResources/skilling/microsoft-security-academy/sentinel-academy)
- [Making Sentinel Work for you (whitepaper)](https://www.microsoft.com/security/blog/2020/07/09/making-azure-sentinel-work/)
- [Become a Microsoft Sentinel Ninja: The Complete level 400 training](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/become-a-microsoft-sentinel-ninja-the-complete-level-400/ba-p/1246310)
- [Best Practices for designing a Microsoft Sentinel or Azure Defender for Cloud Workspace](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/best-practices-for-designing-a-microsoft-sentinel-or-azure/ba-p/832574)
- [Microsoft Sentinel Workbooks 101](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-workbooks-101-with-sample-workbook/ba-p/1409216)
- [Microsoft Sentinel Design Diagram](https://www.managedsentinel.com/azure-sentinel-design-2/)
- [How to use Microsoft Sentinel for Incident Response, Orchestration, and Automation](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/how-to-use-azure-sentinel-for-incident-response-orchestration/ba-p/2242397)
- [Protecting your Github assets with Microsoft Sentinel](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/protecting-your-github-assets-with-azure-sentinel/ba-p/1457721)
- [Advanced multistage attack detection in Microsoft Sentinel (fusion)](https://docs.microsoft.com/en-us/azure/sentinel/fusion)
- [Learning with the Microsoft Sentinel Training Lab](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/learning-with-the-microsoft-sentinel-training-lab/ba-p/2953403)
- [Sentinel To-Go: A Lab w/ Prerecorded Data & Custom Logs Pipe via ARM Template](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-to-go-part1-a-lab-w-prerecorded-data-amp-a-custom/ba-p/1260191)
- [MITRE ATT&CK Framework Reference for Sentinel](https://azurecloudai.blog/2020/07/13/mitre-attack-framework-reference-for-azure-sentinel/)
- [Detecting malware kill chains with Defender & Microsoft Sentinel](https://learnsentinel.blog/2022/02/28/detecting-malware-kill-chains-with-defender-and-microsoft-sentinel/)
- [Joint forces - MS Sentinel and the MITRE framework](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/joint-forces-ms-sentinel-and-the-mitre-framework/ba-p/3191589)
- [Azure Sentinel Side-by-Side with Splunk](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/azure-sentinel-side-by-side-with-splunk/ba-p/1211266)
- [Sentinel All-in-One v2](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/the-azure-solution-architect-map/ba-p/689700)

### Microsoft Defender for Cloud

- [Become a Microsoft Defender for Cloud Ninja](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/become-a-microsoft-defender-for-cloud-ninja/ba-p/1608761)
- [Microsoft Defender for Cloud Labs](https://github.com/Azure/Microsoft-Defender-for-Cloud/tree/main/Labs)
- [Mind Map Azure Defender Threat Protection](https://swiftsolves.substack.com/p/mind-map-azure-defender-threat-protection)
- [Microsoft Defender for Cloud - Coverage Dashboard](https://github.com/Azure/Microsoft-Defender-for-Cloud/tree/main/Workbooks/Defender%20for%20Cloud%20Coverage)
- [Protect your Google Cloud workloads with Microsoft Defender for Cloud](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/protect-your-google-cloud-workloads-with-microsoft-defender-for/ba-p/3073360)
- [How to Effectively Perform a Microsoft Defender for Cloud PoC](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/how-to-effectively-perform-a-microsoft-defender-for-cloud-poc/ba-p/516874)
- [Defender for Cloud Data Flows](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/microsoft-defender-for-cloud-data-flow/ba-p/1382800)

### Identity

- [Microsoft Defender for Identity Ninja Training](http://aka.ms/mdininja)
- [Your Pa$$word doesn't matter](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/your-pa-word-doesn-t-matter/ba-p/731984)
- [Azure Identities and Roles Governance Dashboard At Your Fingertips](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-identities-and-roles-governance-dashboard-at-your/ba-p/3068613)
- [What's the difference between a personal Microsoft account and a work or school account?](https://techcommunity.microsoft.com/t5/itops-talk-blog/what-s-the-difference-between-a-personal-microsoft-account-and-a/ba-p/2241897)
- [Demystifying Service Principals – Managed Identities](https://devblogs.microsoft.com/devops/demystifying-service-principals-managed-identities/)
- [Helping protect against AS-REP Roasting with Microsoft Defender for Identity](https://techcommunity.microsoft.com/t5/security-compliance-and-identity/helping-protect-against-as-rep-roasting-with-microsoft-defender/ba-p/2244089)
- [Manage emergency access accounts in Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/roles/security-emergency-access)
- [SAML vs. OAuth2 vs. OpenID Connect](https://jads.blog/identity-management-saml-vs-oauth2-vs-openid-connect-c9a06548b4c5)
- [Passwordless authentication is now GA](https://techcommunity.microsoft.com/t5/azure-active-directory-identity/passwordless-authentication-is-now-generally-available/ba-p/1994700)
- [Passwordless authentication options for Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/authentication/concept-authentication-passwordless)
- [Recommendations and best practices for Azure Active Directory B2C](https://docs.microsoft.com/en-us/azure/active-directory-b2c/best-practices)
- [Implementing Azure Privileged Identity Management (PIM)](https://blog.ahasayen.com/microsoft-azure-pim/)
- [What is, and how to use Azure B2C Custom Policies?](https://www.cloudpartner.fi/?p=5856)
- [Orphaned Azure Security Principals Clean-up & Azure Policy Managed Identity Role Assignment Automation](https://mortenknudsen.net/?p=938)
- [Enterprise App & Service Principal KeyCredential Assessment](https://github.com/microsoft/aad-app-credential-tools/blob/main/azuread/azuread-app-credential-remediation-guide.md)

### App/Dev

- [Serverless Functions Security](https://docs.microsoft.com/en-us/azure/architecture/serverless-quest/functions-app-security)
- [Azure API Management – What’s what in OAuth2 related settings?](https://securecloud.blog/2021/03/28/azure-api-management-whats-what-in-oauth2-related-settings/amp/)
- [Access Management: Securing APIs using OAuth2.0](https://jads.blog/access-management-securing-apis-using-oauth2-0-b35aea23ad69)
- [Innovation Security](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/secure/innovation-security)
- [DevSecOps Controls](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/secure/devsecops-controls)
- [Microservices Governance](https://medium.com/microservices-learning/introduction-to-microservices-governance-part-iv-3e88228b7e5f)
- [Secure DevOps Kit for Azure](https://github.com/azsk/devopskit)
- [Azure Security for Cloud-Native Apps E-Book](https://learn.microsoft.com/en-us/dotnet/architecture/cloud-native/azure-security)
- [Securing Enterprise DevOps Environments - E-Book](https://azure.microsoft.com/en-us/resources/securing-enterprise-devops-environments/)
- [Manage DecSecOps Posture & Governance with Defender for DevOps](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/manage-devops-security-posture-amp-governance-through-single/ba-p/3807050)

### Data, AI, and IoT

- [Azure data security and encryption best practices](https://docs.microsoft.com/en-us/azure/security/fundamentals/data-encryption-best-practices)
- [Playbook for addressing common security requirements with Azure SQL Database and Azure SQL Managed Instance](https://docs.microsoft.com/en-us/azure/azure-sql/database/security-best-practice)
- [Security in Azure Cosmos DB - overview](https://docs.microsoft.com/en-us/azure/cosmos-db/database-security)
- [Azure IoT Security](https://azure.microsoft.com/en-us/overview/iot/security/)
- [Microsoft Defender for IoT Ninja Training](https://techcommunity.microsoft.com/t5/microsoft-defender-for-iot-blog/microsoft-defender-for-iot-ninja-training/ba-p/2428899)
- [What is Azure Sphere Security Service?](https://www.hackster.io/news/what-is-azure-sphere-security-service-e5708d999a84)
- [Hunting for secrets in Azure Data Factory Pipelines](https://securecloud.blog/2022/02/22/hunting-for-secrets-in-azure-data-factory-pipeline-run-inputs-and-outputs/amp/)
- [AI Risk Assessment](https://github.com/Azure/AI-Security-Risk-Assessment)
- [Six Security Considerations for Machine Learning Solutions](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/six-security-considerations-for-machine-learning-solutions/ba-p/3718592)

### Infrastructure

- [Azure Network Security Ninja Training](https://techcommunity.microsoft.com/t5/azure-network-security-blog/azure-network-security-ninja-training/ba-p/2356101)
- [Azure Network Security Tech Community](https://github.com/Azure/Azure-Network-Security)
- [Interactive Guide - Security with Azure Firewall and DDOS](https://mslearn.cloudguides.com/guides/Secure%20your%20network%20infrastructure%20with%20Azure%20Firewall%20and%20Azure%20DDoS%20Protection)
- [Tutorial Overview: Azure Web Application Firewall Security Protection and Detection Lab](https://techcommunity.microsoft.com/t5/azure-network-security-blog/tutorial-overview-azure-web-application-firewall-security/ba-p/2030423)
- [Best practices for defending Azure Virtual Machines](https://www.microsoft.com/security/blog/2020/10/07/best-practices-for-defending-azure-virtual-machines/)
- [Detections for Azure Firewall in Azure Sentinel](https://techcommunity.microsoft.com/t5/azure-network-security-blog/new-detections-for-azure-firewall-in-azure-sentinel/ba-p/2244958)
- [Parsing Azure Firewall Logs in Microsoft Sentinel](https://medium.com/wortell/parsing-azure-firewall-logs-in-microsoft-sentinel-585ffe1c0565)
- [Center for Threat-Informed Defense teams up with Microsoft, partners to build the ATT&CK® for Containers matrix](https://www.microsoft.com/security/blog/2021/04/29/center-for-threat-informed-defense-teams-up-with-microsoft-partners-to-build-the-attck-for-containers-matrix/)
- [Securing our approach to domain fronting within Azure](https://www.microsoft.com/security/blog/2021/03/26/securing-our-approach-to-domain-fronting-within-azure/)
- [Azure App Service Private Link Integration with Azure Front Door Premium](https://thetechl33t.com/2021/03/01/azure-app-service-private-link-integration-with-azure-front-door-premium/)
- [Detecting Identity Attacks in Kubernetes](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/detecting-identity-attacks-in-kubernetes/ba-p/3232340)
- [Microsoft Networking Academy Youtube](https://www.youtube.com/channel/UCy6v89YQ_u12dsxK4FH0NuA/)
- [PaloAlto NGFW, F5 WAF, and DDos - Azure Architectural Patterns](https://www.sanganakauthority.com/2021/05/paloalto-ngfw-f5-waf-and-ddos-proven.html)
- [Azure Networking is not like your on-prem network](https://blog.cloudtrooper.net/2023/01/21/azure-networking-is-not-like-your-on-onprem-network/)
- [Azure WAF Turning for Web Applications](https://techcommunity.microsoft.com/t5/azure-network-security-blog/azure-waf-tuning-for-web-applications/ba-p/3776133)
- [WAF Comparison Project](https://github.com/openappsec/waf-comparison-project)

### Cryptography

- [Azure encryption overview](https://docs.microsoft.com/en-us/azure/security/fundamentals/encryption-overview)
- [Azure Double Encryption](https://docs.microsoft.com/en-us/azure/security/fundamentals/double-encryption)
- [Azure Data encryption models](https://docs.microsoft.com/en-us/azure/security/fundamentals/encryption-models)
- [Key Vault Managed HSM](https://docs.microsoft.com/en-us/azure/key-vault/managed-hsm/)
- [Azure Key Vault security](https://docs.microsoft.com/en-us/azure/key-vault/general/security-features)
- [Azure Payment HSM](https://docs.microsoft.com/en-us/azure/payment-hsm/overview)
- [Authentication in Azure Key Vault](https://docs.microsoft.com/en-us/azure/key-vault/general/authentication)

### Compliance

- [Azure Compliance Lists](https://docs.microsoft.com/en-us/azure/compliance/)
- [Azure Compliance Offerings](https://docs.microsoft.com/en-us/azure/compliance/offerings/)
- [Azure Global Compliance Map](https://azure.microsoft.com/en-us/resources/azure-global-compliance-map/)
- [National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) in Azure](https://docs.microsoft.com/en-us/compliance/regulatory/offering-nist-csf)
- [Mapping to NIST CSF and ISO 27001](https://aka.ms/CyberMapping)
- [Data Residency in Azure](https://azure.microsoft.com/en-us/global-infrastructure/data-residency/)
- [(Microsoft Compliance) Food and Drug Administration CFR Title 21 Part 11](https://docs.microsoft.com/en-us/compliance/regulatory/offering-FDA-CFR-Title-21-Part-11)
- [(Microsoft Compliance) HIPPA & HITECH ](https://docs.microsoft.com/en-us/compliance/regulatory/offering-hipaa-hitech)
- [(Microsoft Compliance) Health Information Trust Alliance (HITRUST) Common Security Framework (CSF)](https://docs.microsoft.com/en-us/compliance/regulatory/offering-hitrust)
- [Microsoft GxP Cloud Guidelines (Blog)](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/microsoft-gxp-cloud-guidelines/ba-p/1681166)
- [Microsoft Azure GxP Guidelines(Whitepaper)](https://azure.microsoft.com/en-us/resources/microsoft-azure-gxp-guidelines-april/)
- [(Microsoft Compliance) Good Clinical, Laboratory, and Manufacturing Practices (GxP)](https://docs.microsoft.com/en-us/compliance/regulatory/offering-gxp)
- [NIST SP 1800-8 Securing Wireless Infusion Pumps in Healthcare Delivery Organizations](https://csrc.nist.gov/publications/detail/sp/1800-8/final)
- [CIS Benchmark for Azure](https://www.cisecurity.org/benchmark/azure)
- [NIST SP 800-53 Rev. 5 Security and Privacy Controls for Information Systems and Organizations](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [NIST SP 800-171 Rev. 2 Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations](https://csrc.nist.gov/publications/detail/sp/800-171/rev-2/final)

### Misc 

- [Microsoft Incident Response Overview](https://aka.ms/IR)
- [Incident Response Reference Guide](https://aka.ms/IRRG)
- [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/)
- [MITRE ATT&CK](https://attack.mitre.org/versions/v9/)
- [MITRE ATT&CK Cloud Matrix](https://attack.mitre.org/matrices/enterprise/cloud/)
- [MITRE D3FEND](https://d3fend.mitre.org/)
- [Mark's List](https://www.linkedin.com/pulse/marks-list-mark-simos/)
- [Cloud Security Alliance Guidance for Critical Areas of Focus in Cloud Computing](https://cloudsecurityalliance.org/research/guidance/)
- [Cloud Security Alliance - Cloud Threat Modeling](https://cloudsecurityalliance.org/artifacts/cloud-threat-modeling/)
- [NIST 800-144 Guidelines on Security and Privacy in Public Cloud Computing](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-144.pdf)
- [Azure Storm Spotter](https://github.com/Azure/Stormspotter)
- [Florian Roth (Neo23x0)](https://github.com/Neo23x0)
- [Mark's List](https://www.linkedin.com/pulse/marks-list-mark-simos/)
- [Introducing BloodHound 4.0: The Azure Update](https://posts.specterops.io/introducing-bloodhound-4-0-the-azure-update-9b2b26c5e350)

# Contributing

This is a public resource, PRs and issues welcome!