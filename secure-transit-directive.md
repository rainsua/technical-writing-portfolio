---
title: Secure Transit Directive
author: Ramon A. Insua
date: "2026-01-19"
version: 1.0
---
## 1.0 Objective

Cross-border travel brings elevated risks to information security. This includes device seizure, forensic inspection and state-sponsored espionage. This policy establishes standards (mandatory) to minimize the attack surface of digital devices during travel, and to ensure a baseline of security hardening to maximize data confidentiality.

## 2.0 Scope

This policy applies to all persons subject to organizational security mandates, irrespective of role or seniority, when traveling internationally with company assets or BYOD (Bring Your Own Device) hardware used for business purposes.

## 3.0 Rationale

Forensic inspection of digital devices at border crossings presents a critical risk to individuals with valuable digital assets. Adherence to this policy mitigates the risk of data loss/compromise in  cursory inspections and provides Defense-in-Depth against targeted forensic analysis.

## 4.0 Hardware Standards

### 4.1 Sanctioned Devices

Only  **business-grade** or **enterprise-grade** hardware is sanctioned. Consumer-grade devices are forbidden because they lack the security elements necessary to achieve baseline security and the performance/reliability to successfully navigate encryption/decryption and the necessary hardening for this threat model.

### Smartphones

- **Apple iPhones** currently receiving security patches.
- **Samsung Galaxy** Series S and Z currently receiving security updates 
- **Google Pixel** Models currently receiving security patches.

### Laptops

- **Sanctioned** Lenovo ThinkPad and ThinkBook, HP EliteBook and ZBook, Dell Pro/Pro Max, Apple MacBook (Air/Pro).
- **Prohibited** Ruggedized devices (e.g. Panasonic Toughbook) must be avoided unless operationally required, due to disproportionate scrutiny at checkpoints.

## 4.2 "Burner" Devices

A "burner" is a travel-specific device provisioned with minimum-viability data. The device must be sanitized upon return (factory-reset).

## 5.0 Risk Assessment Framework

Travelers must assess their profile against the **Risk Matrix** below.

### 5.1 Personal risk

If the traveler answers **YES** to any of the questions below, the traveler is **High Risk**:

- Are you, or have you ever been an activist, perceived by any government as an adversary?
- Have you published any content that is politically charged on social media.
- Are you objectively considered an influencer or a high-net-worth individual?
- Have you been employed in the Cybersecurity or Defense sectors?
- Would you, due to your appearance, look out of place in a corporate setting, like a bank?
- Do you carry over $10k in crypto? On hot or cold wallets?
- Do you carry material or is there anything about your person potentially criminalized in the destination country?
- Do you have visible tattoos and/or alterations in your person?

## 5.2 Destination Risk Indicators

This policy establishes all destinations at minimum **medium risk** and raises the risk profile where one or more of the following conditions are met:

1. Government instability or civil unrest.
2. Authoritarian legal environment.
3. Pervasive state-sponsored surveillance.

Travelers must consult [**The Economist Intelligence Unit Democratic Index**](https://www.eiu.com/n/campaigns/democracy-index-2024/) and/or [**The Fragile State Index**](https://fragilestatesindex.org/2025/02/18/https-fragilestatesindex-org-wp-content-uploads-2025-02-fsi-2024-report-a-world-adrift-2-pdf/) in the absence of more specialized intelligence.

## 6.0 Operational Security

### 6.1 Data Minimization

- **High Risk Travel:** Travelers must bring only mission-critical data on travel devices across borders.
- **Cloud Dependency:** Non-mission-critical data must be backed up to a secure cloud environment and wiped from local storage on all travel devices.

### 6.2 Baseline Configuration for computers

- Full disk encryption with Bitlocker/FileVault.
    - Bitlocker specifics: **Key escrow by Microsoft is prohibited.** AES-256 encryption algorithm required.
    - Pre-Boot Authentication: PIN (9-digit minimum) required.

- **Power State:** Devices must be fully shutdown (S5 State). All other power states are forbidden to prevent cold boot attacks. 

- Authentication with MFA and passwordless if possible. Numeric PIN/Biometrics for all system access.

- Password manager secured with MFA and a 6-word random (diceware) passphrase which must not be stored anywhere in the traveler's person.

### 6.3 Baseline configuration for phones

- Full-disk encryption.

- Enable ``Lockdown`` mode on **iPhone**/ Auto Blocker in ``maximum restriction`` on **Samsung Galaxy**/**Google Pixel**.

- Screen timeout 30 seconds.

- MFA with biometrics/passwords/tokens.

- Biometric unlock must be disabled before checkpoint crossing. (passphrases/PIN only)

## 7.0 Re-Entry Protocol

### 7.1 Chain of Custody

If the user certifies via signed affidavit that the device(s) **were ALWAYS either in his possession or in direct line of sight** i.e. the chain of custody was never broken, the infosec department may at its sole discretion, waive sanitization protocols. In all other cases irrespective of destination risk the devices will be surrendered to the IT department upon arrival (ASAP) for sanitization. This includes BYOD.

**Tampering & Isolation:** In the event of **suspicion of tampering or interdiction** devices must remain shutdown (in S5 state) and secured in RF-shielded containment (Faraday bags), prior to entering the physical perimeter of company facilities.
