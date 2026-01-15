---
Title: Secure Transit Directive
Author: Ramon A. Insua
Date: 06-11-25
Version: 1.0
---
## 1.0 Objective

Cross-border travel brings elevated risks to information security. This includes device seizure, forensic inspection and state-sponsored espionage. This policy establishes standards (mandatory) to minimize the attack surface of digital devices during travel, and to ensure a baseline of security hardening to maximize data confidentiality.

## 2.0 Scope

This policy applies to all persons subject to organizational security mandates, irrespective of role or seniority, when traveling internationally with company assets or BYOD (Bring Your Own Device) hardware used for business purposes.

## 3.0 Rationale

Forensic inspection of digital devices at border crossings, presents a critical risk to individuals with valuable digital assets. Adherence to this policy mitigates the risk of data loss/compromise in  casual inspections and in-depth defense against targeted forensic analysis.


## 4.0 Hardware Standards

### 4.1 Sanctioned Devices

Only  **business-grade** or **enterprise-grade** hardware is sanctioned. Consumer-grade devices should be avoided because they lack the security elements necessary to achieve baseline security and the performance and reliability to successfully navigate encryption/decryption and the necessary hardening for this threat model.

### Smartphones

- **Apple iPhones** currently receiving security patches.
- **Samsung Galaxy** Series S and Z currently receiving security updates 
- **Google Pixel** Models currently receiving security patches.

### Laptops

- **Sanctioned** Lenovo ThinkPad and ThinkBook, HP EliteBook and ZBook, Dell Pro/Pro Max, Apple MacBook (Air/Pro).
- **Prohibited** Ruggedized devices (e.g. Panasonic Toughbook) must be avoided unless operationally required, due to disproportionate scrutiny at checkpoints.

## 4.2 "Burner" Devices



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

Travelers must consult **The Economist Intelligence Unit Democratic Index**(https://www.eiu.com/n/campaigns/democracy-index-2024/) and/or [**The Fragile State Index**](https://fragilestatesindex.org/2025/02/18/https-fragilestatesindex-org-wp-content-uploads-2025-02-fsi-2024-report-a-world-adrift-2-pdf/) in the absence of more specialized intelligence.

### 4.2 Burner devices

For the purpose of this SOP a "burner" device is a travel-only device provisioned with minimum viability data that will be sanitized when returned home (factory reset).

## Baseline security

### On computers

- Full disk encryption with Bitlocker using PIN lock (9 digits min) and with no key escrow by Microsoft. AES-256 preferred, AES-128 minimum.

- Authentication protocol with MFA and passwordless if possible. Numeric PIN/Biometrics.

- FIPS mode (optional, recommended if you need compliance).

- Password manager secured with MFA and a 6-word random (diceware) passphrase.

- Disable hibernation.

#### Rationale

Microsoft is compelled by law to hand over keys in certain jurisdictions, without need for a court order. 

### On Phones

- Full-disk encryption.

- Enable ``paranoid mode``on **iPhone**/ Auto Blocker in ``maximum restriction`` on **Samsung**.

- Screen timeout 30 seconds.

- MFA with biometrics/passwords/tokens.

- Travel account on password manager syncing via cloud (Bitwarden, 1password, etc...)

## Sanitizing a regular work/personal device for travel

Setting up business-grade hardware for travel is a straightforward process if baseline security is met from the beginning.

In the absence of a burner, non-mission-critical apps and data must be backed up to a secure cloud and wiped on the device. This includes authentication apps and credentials. The creation of a travel password vault is **highly** recommended. This vault should include only passwords and credentials for mission-critical apps. Social media should be avoided at all costs, unless one already has a "second" social media persona made for travel.