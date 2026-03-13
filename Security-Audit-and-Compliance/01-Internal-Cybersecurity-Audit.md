# Case Study: Internal Cybersecurity Audit - Botium Toys
* **Date:** 29/11/2025
* **Status:** Completed
* **Project Type:** GRC
* **Frameworks:** NIST CSF, PCI DSS, GDPR, SOC2

## 1. Background & Scope
This audit was conducted as part of the Google Cybersecurity Professional Certificate for Botium Toys, a fictional retails company experiencing rapid digital growth. As the company expanded its online presence and began processing higher volumes of customer payment data, a formal assessment of its security maturity became necessary.

The objective was to identify security gaps that could lead to operational disruption, legal liabilities, or reputational damage. My focus was on how data, personnel, and internal processes interact to support secure business operations.

## 2. Controls & Compliance Assessment
I utilized a structured checklist to evaluate the current security posture against industry standards. The assessment revealed that while basic preventive tools (like Firewalls) are in place, several critical administrative and technical controls are missing.

### 2.1 Technical & Physical Controls Checklist
| Control | Status |
| **Least Privilege** | ☒ No |
| **Firewall** | ☒ Yes |
| **Disaster Recovery** | ☒ No |
| **IDS** | ☒ No |
| **Password Policies** | ☒ No |
| **Backups** | ☒ No |
| **Encryption** | ☒ No |
| **Antivirus** | ☒ Yes |
| **Physical Locks** | ☒ Yes | 
| **CCTV** | ☒ Yes |

### 2.2 Compliance Gap Analysis
* **PCI DSS:** Critical gaps were identified in how credit card data is stored and processed. Encryption and authorized access controls are not currently meeting requirements.
* **GDPR:** While a breach notification plan exists, there is a lack of proper data classification and inventory for E.U. customer data.
* **SOC2:** Policies for user access and data confidentiality are not currently established, though data integrity remains consistent.

## 3. Auditable Requirements & Ratings
I used a risk-based rating model (Critical, Significant, Important, Minor) to classify the findings based on their potential impact on the organization.

| Domain | Control | Audit Rating |
| Access Control | Least Privilege & Separation of Duties | Critical |
| Data Protection | Encryption of sensitive data | Critical |
| Business Continuity | Backups and Disaster Recovery | Critical |
| Network Security | Intrusion Detection System (IDS) | Significant |
| Asset Management | Inventory and Classification | Significant |

## 4. Findings & Strategic Recommendations
The audit identified high exposure to risk due to incomplete controls over critical data assets. To address these gaps, **I developed** the following prioritized recommendations:

| Finding | Rating | Recommended Action | Priority |
| Excessive access to data | Critical | Implement Least Privilege and Separation of Duties. | 1 |
| Unprotected payment data | Critical | Implement Encryption at rest and in transit. | 1 |
| Lack of recovery | Critical | Establish formal Backups and Disaster Recovery plans. | 1 |
| Limited threat detection | Significant | Deploy an Intrusion Detection System (IDS). | 2 |

## 5. Lessons Learned
This project highlighted that security is not just about having a firewall. I learned that a lack of formal governance and "human-level" controls (like Least Privilege) can make even the best technical tools ineffective. My recommendation for Botium Toys is to prioritize the Critical access and data protection gaps to meet baseline compliance and protect customer trust.

