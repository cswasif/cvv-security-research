# CVV Validation Vulnerabilities in In-App Payment Systems

## Executive Summary

This document extracts and analyzes critical vulnerabilities related to Card Verification Value (CVV) validation in in-app payment systems as identified in the paper "Revisiting Online Privacy and Security Mechanisms Applied in the In-App Payment Realm from the Consumers' Perspective." The findings align with the thesis focus on non-AI based prevention strategies, stringent server-side CVV validation, and PCI DSS compliance implications. The paper reveals significant security gaps in how mobile applications handle CVV data during payment processing, creating opportunities for Card-Not-Present (CNP) fraud.

## Key CVV Validation Vulnerabilities

### 1. Lack of Secondary Encryption for CVV Data

The paper reveals a critical vulnerability where CVV data is transmitted with inadequate protection:

- **Plain Text CVV After TLS Decryption**: The researchers found that "credit card numbers, full owner name, and the CVV security code exist in plain text when purchasing with L'Osteria app while paying with Mastercard/Visa option."

- **Single Layer Protection**: Most analyzed applications rely solely on TLS encryption for protecting CVV data, with no additional encryption layers. As the paper states: "most analyzed apps do not use additional security measures to encrypt the user's data after TLS encryption."

- **Missing Security Best Practices**: The researchers note that "additional security measures such as hashing and salting the password and email address would have been desirable" but were absent in most applications.

### 2. Vulnerable Server-Side CVV Validation

The paper identifies server-side vulnerabilities that compromise CVV validation:

- **Inadequate API Security**: The research found that "the app developer's information about the APIs used in the apps is unclear," leading to inconsistent security implementations for CVV validation.

- **Insecure Data Handling**: The paper states that "in-app and browser-based payments have the same behavior" regarding security vulnerabilities, suggesting that server-side CVV validation suffers from similar weaknesses across platforms.

### 3. CVV Data Exposure to Third Parties

The research uncovered concerning practices where CVV data could potentially be exposed to unauthorized third parties:

- **Excessive Third-Party Connections**: During payment processing, applications established connections with numerous third-party servers. For example, "MyProtein, which communicates with 74 different trackers in 24 locations worldwide during the purchase process."

- **Payment Data Sharing**: The researchers found that "purchase-relevant attributes" were shared with third parties, creating potential exposure points for sensitive CVV data.

- **Unexpected Data Recipients**: The paper notes "communications with servers neither listed in the privacy policies of the apps nor the static analysis," indicating that CVV data might be transmitted to undisclosed recipients.

### 4. Man-in-the-Middle Attack Vulnerability

The researchers successfully executed a man-in-the-middle attack that compromised CVV data:

- **TLS Interception**: The study demonstrated how "attackers can exploit this situation, especially when a consumer orders and the phone is connected to public networks."

- **Successful CVV Extraction**: The researchers were able to "filter out the cardholder, our credit card number, expiration date, and the three-digit CVV security code of the card from the traffic."

- **JSON Format Exposure**: In most cases, this sensitive information "was readable together in a packet in JSON format," making it easily parseable and exploitable.

## Implications for CVV Security

### Security Architecture Weaknesses

- **Insufficient Defense-in-Depth**: The applications failed to implement multiple layers of security for CVV protection, relying almost exclusively on TLS encryption.

- **Lack of Secure Coding Practices**: The paper highlights that "security and privacy dubious practices are still unsolved" despite previous research highlighting these vulnerabilities.

- **Inconsistent Security Implementation**: The research found "significant differences in the qualitative use of the trackers" and security measures across different applications.

### Persistent Vulnerabilities

- **Known Issues Remain Unaddressed**: The paper concludes that "despite efforts of the research community to highlight security flaws and bring recommendations for fixing these problems, fintech companies still have work to do to fix these long-lasting vulnerabilities."

- **Inadequate Progress**: Comparing with previous research, the paper notes that "security and privacy dubious practices are still unsolved," indicating a lack of progress in addressing CVV security issues.

## Conclusion

The paper reveals significant vulnerabilities in how in-app payment systems handle CVV validation, creating opportunities for Card-Not-Present fraud. The findings align with the thesis focus on the need for enhanced CVV validation and stricter PCI DSS compliance. The vulnerabilities identified demonstrate that current server-side CVV validation practices are inadequate and require substantial improvement to protect against evolving cyber threats.

These findings provide concrete evidence of the thesis premise that systems are accepting transactions despite missing or bypassed CVV data protection, undermining the security of digital transactions. The research supports the need for stringent server-side CVV validation and secure merchant integration practices as advocated in the thesis abstract.