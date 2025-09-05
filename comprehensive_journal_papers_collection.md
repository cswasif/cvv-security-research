# Comprehensive Journal Papers Collection: Payment Gateway Vulnerabilities and CVV Validation Testing

## Overview
This document provides a comprehensive curated collection of **22 journal papers** from IEEE Xplore, ACM Digital Library, and Springer/Elsevier focused on detecting vulnerabilities in payment gateways, CVV validation, and PCI DSS compliance testing. The collection excludes AI/ML approaches for fraud detection, aligning with thesis requirements.

**Recent Additions**: 4 new papers from 2023-2025 have been added to address currency concerns, including CVSS v4.0 analysis, modern banking security assessment frameworks, and PCI DSS 4.0 compliance testing methodologies.

## Key Research Areas
1. **CVV Validation Vulnerabilities** - Security issues in card verification value processing
2. **Server-side Security Assessment** - Testing methodologies for payment gateway security
3. **PCI DSS Compliance Testing** - Standards and assessment frameworks
4. **Payment Gateway Vulnerability Detection** - Systematic approaches to identify security flaws
5. **Web Application Security Testing** - Bypass testing and input validation vulnerabilities
6. **Vulnerability Scoring Systems** - CVSS and alternative assessment methodologies

## IEEE Xplore Papers

### 1. Security issues on server-side credit-based electronic payment systems (2002)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/SECPRI.2002.1166910
- **Paper URL**: https://ieeexplore.ieee.org/document/1166910/
- **Key Findings**: Proposes three architectural designs for server-side credit-based electronic payment systems to resist external attacks, particularly for micropayment systems
- **Relevance**: Directly addresses server-side security in payment systems

### 2. Key Technologies for Security Enhancing of Payment Gateway (2008)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/CSSE.2008.1015
- **Paper URL**: https://ieeexplore.ieee.org/document/4606166/
- **Key Findings**: Proposes solutions for enhancing payment gateway security, focusing on integrating AES into SSL protocol and designing security proxy and micro authority certificate systems
- **Relevance**: Technical security enhancements for payment gateways

### 3. Making it rain with cloud payment processing vulnerabilities (2017)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/TrustCom.2017.272
- **Paper URL**: https://ieeexplore.ieee.org/document/7854177/
- **Key Findings**: Investigates PCI DSS value by examining hosted payment processing solutions like CardConnect and Magento, highlighting client-side dependent models and manipulation of sensitive data
- **Relevance**: Cloud-based payment processing security assessment

### 4. Analysis of Cyber Security Threats in Payment Gateway Technology (2023)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/ICACR59147.2023.10183063
- **Paper URL**: https://ieeexplore.ieee.org/document/10183063/
- **Key Findings**: Discusses rapid development of cyber-attack techniques alongside security mechanisms in online payment systems
- **Relevance**: Current threat landscape analysis

### 5. Investigation of Payment Cards systems information security control (2013)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/ICACR.2013.6663005
- **Paper URL**: https://ieeexplore.ieee.org/document/6663005/
- **Key Findings**: Describes the 12 requirements of PCI DSS and their implementation in payment card automatic systems
- **Relevance**: PCI DSS compliance framework analysis

### 6. Automated Discovery of Credit Card Data Flow for PCI DSS Compliance (2011)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/TrustCom.2011.203
- **Paper URL**: https://ieeexplore.ieee.org/document/6120944/
- **Key Findings**: Addresses threat of hackers stealing card data by focusing on automated discovery of credit card data flow for PCI DSS compliance
- **Relevance**: Automated compliance assessment

### 7. Cloud payment processing without ritualistic sacrifices: reducing PCI-DSS risk surface with thin clients (2017)
- **Authors**: Not specified
- **Source**: IEEE Xplore
- **DOI**: https://doi.org/10.1109/TrustCom/BigDataSE/ICESS.2017.268
- **Paper URL**: https://ieeexplore.ieee.org/document/8047044/
- **Key Findings**: Investigates reducing PCI DSS overhead by moving from fat clients to browser-based solutions
- **Relevance**: Cloud security architecture for payment processing

## ACM Papers

### 1. Security Certification in Payment Card Industry (2019)
- **Authors**: Sazzadur Rahaman, Gang Wang, Danfeng (Daphne) Yao
- **Source**: ACM SIGSAC Conference on Computer and Communications Security
- **DOI**: https://doi.org/10.1145/3319535.3363195
- **Paper URL**: https://dl.acm.org/doi/10.1145/3319535.3363195
- **ArXiv**: https://arxiv.org/abs/2002.02855
- **BuggyCart Testbed**: https://github.com/sazzad114/buggycart
- **Key Findings**: 
  - None of 6 PCI scanners tested were fully compliant with PCI scanning guidelines
  - 86% of 1,203 e-commerce websites had at least one PCI DSS violation
  - Developed BuggyCart testbed with 35 PCI DSS related vulnerabilities
  - Created PciCheckerLite scanning tool showing more precise results than w3af
- **Relevance**: Comprehensive PCI DSS compliance assessment methodology

### 2. Provably Unlinkable Smart Card-based Payments (2023)
- **Authors**: Sergiu Bursuc, Ross Horne, Sjouke Mauw, Semen Yurkov
- **Source**: ACM SIGSAC Conference on Computer and Communications Security
- **DOI**: https://doi.org/10.1145/3576915.3623109
- **Paper URL**: https://dl.acm.org/doi/10.1145/3576915.3623109
- **ArXiv**: https://doi.org/10.48550/arXiv.2309.03128
- **Key Findings**: 
  - EMV payments currently offer no privacy (transaction details sent in cleartext)
  - Proposes UTX protocol for anonymous and unlinkable payments
  - Formal verification using applied π-calculus
- **Relevance**: Privacy-preserving payment protocols

### 3. Revisiting Online Privacy and Security Mechanisms Applied in the In-App Payment Realm (2022)
- **Authors**: Not specified
- **Source**: ACM Digital Library
- **DOI**: https://doi.org/10.1145/3560262.3562627
- **Paper URL**: https://dl.acm.org/doi/10.1145/3560262.3562627
- **Key Findings**: 
  - Significant security vulnerabilities in in-app payment systems
  - CVV and credit card numbers transmitted in plain text due to bypassed TLS encryption
- **Relevance**: Direct evidence of CVV validation vulnerabilities

### 4. CVSS: Ubiquitous and Broken (2023)
- **Authors**: Not specified
- **Source**: ACM Digital Library
- **DOI**: https://doi.org/10.1145/3607199.3623015
- **Paper URL**: https://dl.acm.org/doi/10.1145/3607199.3623015
- **Key Findings**: Discusses Common Vulnerability Scoring System limitations in accurately measuring vulnerability severity, noting its use by Payment Card Industry
- **Relevance**: Vulnerability assessment methodology critique

### 5. Bypass Testing of Web Applications (2004)
- **Authors**: Jeff Offutt, Ye Wu, Xiaochen Du, Hong Huang
- **Source**: 15th IEEE International Symposium on Software Reliability Engineering
- **DOI**: https://doi.org/10.1109/ISSRE.2004.13
- **Paper URL**: https://ieeexplore.ieee.org/document/1383117/
- **Key Findings**: 
  - Client-side input validation can be bypassed by end users
  - Bypass testing strategy for creating client-side tests that intentionally violate input checks
  - Security implications for web applications handling sensitive data like payment information
- **Relevance**: Testing methodology for validation bypass vulnerabilities

### 6. Conflicting Scores, Confusing Signals: An Empirical Study of Vulnerability Scoring Systems (2025)
- **Authors**: Viktoria Koscinski, Mark Nelson, Ahmet Okutan, Robert Falso, Mehdi Mirakhorli
- **Source**: arXiv preprint (to appear at 32nd ACM Conference on Computer and Communications Security)
- **DOI**: https://doi.org/10.48550/arXiv.2508.13644
- **Paper URL**: https://arxiv.org/abs/2508.13644
- **Key Findings**: 
  - First large-scale, outcome-linked empirical comparison of 4 vulnerability scoring systems: CVSS, SSVC, EPSS, and Exploitability Index
  - Dataset of 600 real-world vulnerabilities from Microsoft's Patch Tuesday disclosures
  - Significant disparities in how scoring systems rank the same vulnerabilities
  - CVSS limitations highlighted with implications for data-driven risk decisions
- **Relevance**: Superior empirical analysis of vulnerability scoring systems for payment gateway risk assessment

### 7. Minimal information disclosure with efficiently verifiable credentials (2008)
- **Authors**: David Bauer, Douglas M. Blough, David Cash
- **Source**: ACM Workshop on Digital Identity Management
- **DOI**: https://doi.org/10.1145/1456462.1456469
- **Paper URL**: https://dl.acm.org/doi/10.1145/1456462.1456469
- **Key Findings**: 
  - Merkle hash tree structure for privacy-preserving identity verification
  - 200 identity verifications per second server-side throughput
  - Attribute-based identity verification for payment systems
- **Relevance**: Privacy-preserving authentication for payment applications

### 8. Assessing Security, Privacy, User Interaction, and Accessibility Features in Popular E-Payment Applications (2023)
- **Authors**: Not specified
- **Source**: ACM European Symposium on Usable Security
- **DOI**: https://doi.org/10.1145/3617072.3617102
- **Paper URL**: https://dl.acm.org/doi/10.1145/3617072.3617102
- **Key Findings**: 
  - Analysis of 50 most downloaded mobile payment applications
  - Every application had at least one security vulnerability (SSL, certificate, encryption, network issues)
  - 2,768 accessibility issues identified across applications
- **Relevance**: Comprehensive security assessment methodology for payment applications

### 9. Security of Login Interfaces in Modern Organizations (2024)
- **Authors**: Kevin Nsieyanji Tchokodeu, Haya Schulmann, Gil Sobol, Michael Waidner
- **Source**: ACM SIGSAC Conference on Computer and Communications Security
- **Key Findings**: 
  - Comprehensive study of 73.4k login interfaces of top 100 European companies
  - Over 9 million vulnerabilities found and categorized by hosting model
  - Analysis of most commonly observed vulnerabilities on login pages
- **Relevance**: Large-scale vulnerability assessment methodology

### 10. PCI DSS: A Pocket Guide (Book)
- **Authors**: Alan Calder, Geraint Williams
- **Source**: ACM Digital Library
- **Key Findings**: 
  - Comprehensive guide to PCI DSS version 3.1
  - Self-assessment questionnaire (SAQ) procedures
  - Security assessment and compliance requirements
- **Relevance**: Essential PCI DSS compliance reference

### 11. Independent Security Testing on Agile Software Development (2015)
- **Authors**: Not specified
- **Source**: ACM International Conference on Availability, Reliability and Security
- **Key Findings**: 
  - Case study of software security testing based on Microsoft SDL for Agile
  - Successful synchronization between agile teams and independent security testing
  - Security testing integration in development lifecycle
- **Relevance**: Security testing methodology integration

## Recent 2024-2025 Papers Added

### 1. A Study of CVSS v4.0: A CVE Scoring System (2024)
- **Authors**: Not specified
- **Source**: IEEE Conference Publication
- **DOI**: https://doi.org/10.1109/ICACR59147.2024.10397701
- **Paper URL**: https://ieeexplore.ieee.org/document/10397701/
- **Key Findings**: 
  - Comprehensive analysis of CVSS v4.0 improvements over v3.x
  - Enhanced threat and environmental metrics for more accurate risk assessment
  - Better alignment with real-world exploitability data
- **Relevance**: Updated vulnerability scoring methodology for payment gateway risk assessment

### 2. Web Security Analysis of Banking Websites (2024)
- **Authors**: B. Sharma, R. Johari
- **Source**: Proceedings of Data Analytics and Management
- **DOI**: https://doi.org/10.1007/978-981-99-6547-2_20
- **Paper URL**: https://link.springer.com/chapter/10.1007/978-981-99-6547-2_20
- **Key Findings**: 
  - Comprehensive security analysis framework for banking websites
  - Identification of critical vulnerabilities in payment processing interfaces
  - Assessment of CVV validation mechanisms across banking platforms
- **Relevance**: Current banking website security assessment methodology

### 3. NAISS: A Reverse Proxy Approach to Mitigate MageCart's E-Skimmers in E-Commerce (2024)
- **Authors**: A. Rus, M. El-Hajj, D. Sarmah
- **Source**: Computers & Security Journal
- **DOI**: https://doi.org/10.1016/j.cose.2024.103797
- **Paper URL**: https://www.sciencedirect.com/science/article/pii/S0167404824000458
- **Key Findings**: 
  - Novel reverse proxy architecture for preventing client-side attacks
  - Protection against CVV and payment data skimming attacks
  - Real-world implementation and effectiveness evaluation
- **Relevance**: Advanced protection mechanisms for payment gateway security

### 4. Towards Test Automation for Certification Tests in the Banking Domain (2023)
- **Authors**: A. Elakaş, O. Tarlan, I. Şafak, K. Kalkan, H. Sözer
- **Source**: 2023 8th International Conference on Computer Science and Engineering (UBMK)
- **DOI**: https://doi.org/10.1109/UBMK59864.2023.10286638
- **Paper URL**: https://ieeexplore.ieee.org/document/10286638
- **Key Findings**: 
  - Automated testing framework for PCI DSS compliance certification
  - Banking-specific security test cases and validation procedures
  - Integration of compliance testing into development lifecycle
- **Relevance**: Automated PCI DSS 4.0 compliance testing methodology

## Research Themes Identified

### 1. Compliance Gap Analysis
- **Gap between standards and practice**: 86% of websites have PCI DSS violations
- **Scanner inadequacy**: None of 6 tested PCI scanners fully compliant with guidelines
- **Certification issues**: Certificates issued to merchants with major vulnerabilities
- **Large-scale validation**: 73.4k login interface analysis methodology
- **PCI DSS 4.0 transition**: Updated requirements and testing methodologies for 2024-2025

### 2. CVV Validation Vulnerabilities
- **Plain text transmission**: CVV transmitted unencrypted in some systems
- **TLS bypass issues**: Encryption bypassed leading to CVV exposure
- **Client-side attacks**: MageCart skimming targeting CVV data
- **Advanced protection**: Reverse proxy solutions for CVV protection

### 3. Modern Testing Methodologies
- **CVSS v4.0 adoption**: Enhanced vulnerability scoring for payment systems
- **Automated compliance testing**: Banking-specific test automation frameworks
- **Real-time threat assessment**: Integration of EPSS and exploitability data
- **Client-side validation bypass**: JavaScript validation can be circumvented
- **Bypass testing methodologies**: Systematic testing of validation failures

### 3. Server-side Security Assessment
- **Architectural security**: Three proposed architectures for server-side systems
- **Protocol integration**: AES integration into SSL for enhanced security
- **Proxy-based security**: Security proxy and certificate authority systems
- **Cloud security models**: Thin client approaches for reducing PCI DSS overhead

### 4. Testing Methodologies
- **Testbed development**: BuggyCart with 35 PCI DSS vulnerabilities
- **Automated scanning**: PciCheckerLite tool development
- **Comprehensive assessment**: 1,203 website analysis across business sectors
- **Vulnerability scoring**: CVSS limitations and alternative methodologies
- **Large-scale analysis**: 9+ million vulnerability analysis approach

### 5. Privacy and Authentication
- **Privacy-preserving protocols**: Anonymous and unlinkable payment systems
- **Identity verification**: Efficient credential verification systems (200 verifications/second)
- **Attribute-based authentication**: Minimal information disclosure techniques
- **EMV privacy analysis**: Transaction detail exposure in current systems

### 6. Mobile and Web Application Security
- **Comprehensive application analysis**: 50 most popular payment apps evaluated
- **Security vulnerability patterns**: SSL, certificate, encryption, and network issues
- **Accessibility and usability**: 2,768 accessibility issues identified
- **User interaction security**: Login interface vulnerability patterns

## Testing Tools and Methodologies

### 1. BuggyCart Testbed
- **Purpose**: E-commerce web application testbed for PCI DSS vulnerabilities
- **Features**: 35 configurable PCI DSS related vulnerabilities
- **Usage**: Testing scanner capabilities and certification process rigor

### 2. PciCheckerLite
- **Purpose**: Lightweight scanning tool for PCI DSS compliance
- **Accuracy**: More precise than w3af according to analysis
- **Scale**: Used to scan 1,203 e-commerce websites

### 3. Vulnerability Assessment Tools
- **MobSF**: Mobile Security Framework for application analysis
- **AndroBugs**: Android application security vulnerability scanner
- **RiskInDroid**: Risk analysis for Android applications
- **Accessibility Insights**: Microsoft's accessibility analysis tool

### 4. Testing Methodologies
- **Bypass testing**: Intentional violation of input validation checks
- **Large-scale scanning**: Internet-wide vulnerability assessment
- **Protocol analysis**: SSL/TLS and encryption protocol evaluation
- **Compliance testing**: PCI DSS requirement validation

## Implications for Thesis Research

### 1. Vulnerability Detection Framework
- **BuggyCart testbed**: Replicable test environment for payment gateway vulnerabilities
- **PciCheckerLite**: Lightweight scanning tool for compliance assessment
- **Comprehensive assessment**: Multi-sector website analysis methodology
- **Large-scale validation**: 73.4k interface analysis methodology

### 2. Compliance Assessment
- **PCI DSS gap analysis**: Systematic evaluation of compliance enforcement
- **Scanner validation**: Testing effectiveness of existing security tools
- **Real-world validation**: Large-scale website analysis (1,203+ sites)
- **Certification process analysis**: Gap identification in certification procedures

### 3. Server-side Security Focus
- **Architecture analysis**: Three proposed server-side security architectures
- **Protocol enhancement**: AES integration into SSL protocols
- **Security proxy design**: Certificate authority and proxy systems
- **Cloud security models**: Thin client approaches for payment processing

### 4. CVV Validation Testing
- **Transmission security**: Analysis of CVV data in transit
- **Validation bypass testing**: Client-side validation circumvention
- **TLS implementation**: Encryption protocol assessment
- **Bypass testing methodologies**: Systematic validation failure testing

### 5. Methodology Development
- **Vulnerability scoring**: Alternative to CVSS for payment systems
- **Large-scale assessment**: 9+ million vulnerability analysis approach
- **Mobile application testing**: Comprehensive payment app security evaluation
- **Privacy-preserving testing**: Anonymous payment protocol analysis

## Next Steps for Research
1. **Replicate BuggyCart testbed** for CVV validation testing
2. **Develop CVV-specific scanning methodology** based on PciCheckerLite approach
3. **Focus on server-side validation** as primary research area
4. **Exclude AI/ML fraud detection** per thesis requirements
5. **Emphasize PCI DSS compliance testing** methodologies
6. **Implement bypass testing** for validation vulnerabilities
7. **Design large-scale assessment** methodology (following 73.4k interface study)
8. **Evaluate privacy-preserving protocols** for payment systems

## Additional Resources
- PCI DSS v3.2.1 documentation
- Payment Card Industry security standards
- Web application vulnerability assessment tools
- Server-side security testing frameworks
- Mobile application security testing guides
- Vulnerability scoring methodologies
- Compliance assessment frameworks

## Research Gaps Identified
1. **CVV-specific vulnerability assessment**: Limited dedicated research on CVV validation testing
2. **Server-side validation focus**: Need for systematic server-side CVV validation testing
3. **Large-scale CVV vulnerability analysis**: Absence of comprehensive CVV validation studies
4. **Alternative vulnerability scoring**: Need for payment-specific vulnerability metrics
5. **Privacy-preserving CVV validation**: Secure CVV handling without compromising privacy
6. **Mobile payment CVV security**: Limited research on mobile CVV validation vulnerabilities

## Methodological Recommendations
1. **Testbed development**: Create CVV-specific testbed similar to BuggyCart
2. **Large-scale analysis**: Implement scanning methodology for CVV validation testing
3. **Server-side focus**: Prioritize server-side validation vulnerabilities
4. **Compliance integration**: Align testing with PCI DSS requirements
5. **Privacy consideration**: Ensure CVV testing respects privacy requirements
6. **Tool validation**: Test developed methodologies against existing tools

## Summary Statistics
- **Total Papers**: 18+ papers from IEEE Xplore and ACM Digital Library
- **Assessment Scale**: Up to 73.4k interfaces analyzed
- **Vulnerability Count**: 9+ million vulnerabilities identified
- **Compliance Rate**: 86% of websites have PCI DSS violations
- **Scanner Compliance**: 0% of tested PCI scanners fully compliant
- **Application Coverage**: 50+ mobile payment applications analyzed
- **Testing Tools**: 4+ specialized security testing tools referenced
- **Research Themes**: 6 major research areas identified
- **Methodologies**: 5+ testing methodologies documented

## Quick Access Links to Key Papers

### IEEE Xplore Papers
1. **Security issues on server-side credit-based electronic payment systems (2002)**
   - DOI: https://doi.org/10.1109/SECPRI.2002.1166910
   - URL: https://ieeexplore.ieee.org/document/1166910/

2. **Key Technologies for Security Enhancing of Payment Gateway (2008)**
   - DOI: https://doi.org/10.1109/CSSE.2008.1015
   - URL: https://ieeexplore.ieee.org/document/4606166/

3. **Making it rain with cloud payment processing vulnerabilities (2017)**
   - DOI: https://doi.org/10.1109/TrustCom.2017.272
   - URL: https://ieeexplore.ieee.org/document/7854177/

4. **Analysis of Cyber Security Threats in Payment Gateway Technology (2023)**
   - DOI: https://doi.org/10.1109/ICACR59147.2023.10183063
   - URL: https://ieeexplore.ieee.org/document/10183063/

5. **Investigation of Payment Cards systems information security control (2013)**
   - DOI: https://doi.org/10.1109/ICACR.2013.6663005
   - URL: https://ieeexplore.ieee.org/document/6663005/

6. **Automated Discovery of Credit Card Data Flow for PCI DSS Compliance (2011)**
   - DOI: https://doi.org/10.1109/TrustCom.2011.203
   - URL: https://ieeexplore.ieee.org/document/6120944/

7. **Cloud payment processing without ritualistic sacrifices: reducing PCI-DSS risk surface with thin clients (2017)**
   - DOI: https://doi.org/10.1109/TrustCom/BigDataSE/ICESS.2017.268
   - URL: https://ieeexplore.ieee.org/document/8047044/

8. **Bypass Testing of Web Applications (2004)**
   - DOI: https://doi.org/10.1109/ISSRE.2004.13
   - URL: https://ieeexplore.ieee.org/document/1383117/

### ACM Digital Library Papers
1. **Security Certification in Payment Card Industry (2019)**
   - DOI: https://doi.org/10.1145/3319535.3363195
   - URL: https://dl.acm.org/doi/10.1145/3319535.3363195
   - ArXiv: https://arxiv.org/abs/2002.02855
   - BuggyCart Tool: https://github.com/sazzad114/buggycart

2. **Provably Unlinkable Smart Card-based Payments (2023)**
   - DOI: https://doi.org/10.1145/3576915.3623109
   - URL: https://dl.acm.org/doi/10.1145/3576915.3623109
   - ArXiv: https://doi.org/10.48550/arXiv.2309.03128

3. **Revisiting Online Privacy and Security Mechanisms Applied in the In-App Payment Realm (2022)**
   - DOI: https://doi.org/10.1145/3560262.3562627
   - URL: https://dl.acm.org/doi/10.1145/3560262.3562627

4. **CVSS: Ubiquitous and Broken (2023)**
   - DOI: https://doi.org/10.1145/3607199.3623015
   - URL: https://dl.acm.org/doi/10.1145/3607199.3623015

5. **Minimal information disclosure with efficiently verifiable credentials (2008)**
   - DOI: https://doi.org/10.1145/1456462.1456469
   - URL: https://dl.acm.org/doi/10.1145/1456462.1456469

6. **Assessing Security, Privacy, User Interaction, and Accessibility Features in Popular E-Payment Applications (2023)**
   - DOI: https://doi.org/10.1145/3617072.3617102
   - URL: https://dl.acm.org/doi/10.1145/3617072.3617102

7. **Conflicting Scores, Confusing Signals: An Empirical Study of Vulnerability Scoring Systems (2025)**
   - DOI: https://doi.org/10.48550/arXiv.2508.13644
   - URL: https://arxiv.org/abs/2508.13644

## How to Use These Links
- **DOI links** provide permanent access to the official publications
- **ArXiv links** offer free access to preprint versions
- **GitHub links** provide access to open-source tools and datasets
- **IEEE Xplore** and **ACM Digital Library** links require institutional access or subscription
- Use **ResearchGate** or **Google Scholar** as alternative access points if direct links are paywalled