Security Audit Report: Course 5 (IT Security)


 IT Security – Defense Against the Digital Dark Arts


Submission Date: 13 February 2026

Auditor: Nandipha Swana


 Executive Summary

This report presents the results of a basic security audit performed on a Windows computer. The purpose of the audit was to check important security features such as password protection, firewall status, threat protection, and operating system updates.

The audit found that several core security features are working correctly, including authentication and firewall protection. However, the operating system is outdated and no longer receives security updates, which creates a potential security risk. Some security settings also require further configuration to improve system protection.

 Introduction

Cybersecurity is an important part of protecting computer systems from threats such as malware, hackers, and data theft. This audit was performed as part of the course IT Security – Defense Against the Digital Dark Arts.

The audit follows the principle of Defense in Depth, which means using multiple layers of security to protect a system. If one security measure fails, other protections are still in place to reduce the risk.

The purpose of this audit was to review key security settings on a Windows system and identify areas where improvements can be made.

 Security Audit Checklist
| Security Control | Status | Audit Findings / Actions Taken |
|------------------|--------|--------------------------------|
| Authentication | ✅ Verified | Implemented strong, unique local account credentials. Password complexity requirements met. |
| Firewall | ✅ Verified | Confirmed that Domain, Private, and Public network firewall profiles are active to prevent unauthorized access. |
| Threat Protection | ⚠️ Ongoing | Identified "Actions recommended" in Windows Security under Account Protection. Configuration improvements are currently being addressed. |
| Updates | ✅ Verified | Checked Windows Update settings and performed a system scan to verify that the operating system is updated. |

1. Identity & Authentication


User authentication serves as the first line of defense for the system, ensuring that only verified users can interact with the workstation. During the audit, account sign-in configurations were reviewed to verify that password-based protection is active and enforced.

The implementation of strong, unique credentials is critical to mitigating the risk of unauthorized access. It is recommended that password hints, if utilized, are kept obscure to prevent social engineering or credential guessing attacks.

<img width="1088" height="715" alt="image" src="https://github.com/user-attachments/assets/f57300d9-78d8-45f3-ac8d-eaab937f2c1e" />



2️⃣ Endpoint Security & System Health


The Windows Security dashboard serves as the central command for monitoring system health and threat protection. An audit of this interface was performed to evaluate the endpoint's current security posture.

Audit Observations:

General Health: The system reports no active threats, indicating that real-time protection is functional.

Account Protection: The audit identified that the 'Account Protection' area requires remediation, as it is currently flagged with 'Actions recommended'.

Analysis & Impact:
While critical active threats are not present, leaving 'Account Protection' unconfigured exposes the system to identity-based risks. Prioritizing the configuration of identity verification methods (such as Windows Hello or Dynamic Lock) is essential for hardening the endpoint against unauthorized access.

<img width="960" height="782" alt="image" src="https://github.com/user-attachments/assets/e63e10e3-089c-421e-bb48-84a2681afbc9" />


3️⃣ Network Perimeter Security (Firewall)


The firewall acts as a protective barrier between the computer and the internet. It monitors incoming and outgoing network traffic and blocks unauthorized connections to ensure a secure network perimeter.

Audit Observation:
During the audit, the firewall status was verified through the Control Panel. The inspection confirmed that firewall protection is fully enabled and active.

Management Status: It was observed that firewall management is currently delegated to Avast Antivirus rather than the default Windows Defender settings.

Security Implication: Because firewall rules and policies are governed by the Avast suite, it is essential to monitor the Avast interface for network-specific security configurations. This confirms that the third-party application is the current "source of truth" for all active network security rules on this workstation.

<img width="817" height="582" alt="image" src="https://github.com/user-attachments/assets/8d8aaa0a-9791-4976-adee-a349edcecc80" />

<img width="780" height="566" alt="image" src="https://github.com/user-attachments/assets/bc128a56-6610-464f-89aa-7baf6bcbf6b5" />


4️⃣ Software & Update Lifecycle

Keeping software updated is the most fundamental aspect of defensive security. During the audit, the Windows Update settings were reviewed to determine if the system is receiving active security patches.

Audit Finding: The system has reached "End of Support." This means it is no longer receiving security updates, leaving it exposed to known and future vulnerabilities that will never be patched.

Security Impact: Running an unsupported OS is a critical risk. Without regular patches, the system is susceptible to exploit kits and malware that target older, unpatched versions of Windows.

<img width="804" height="683" alt="image" src="https://github.com/user-attachments/assets/ca07c9f3-a500-43dc-b0d9-f44651976df4" />


 Future Recommendations

To improve system security, the following actions are recommended:

Enable BitLocker Encryption
This will protect sensitive data by encrypting the entire hard drive.

Set Up Regular Backups
Regular backups will help recover important data in case of system failure or cyber attacks.

Upgrade the Operating System
Install a supported and updated version of Windows to ensure the system continues receiving security patches.

 Conclusion

The security audit confirmed that some important protections such as firewall and authentication are working correctly. However, the outdated operating system represents a major security concern.

By updating the system, configuring additional security settings, and maintaining regular security checks, the overall protection of the computer can be significantly improved.

This audit demonstrates the importance of regularly reviewing system security to defend against digital threats.
