---
Title: 
Author: Ramon A. Insua
Date: 06-11-25
Version: 1.0
---
## Objective

Cross-border travel brings increasingly crucial risks to information security. This includes seizure, forensic inspection and state-sponsored espionage. This policy aims to minimize the attack surface of digital devices during travel, and to ensure a baseline of security hardening to maximize confidentiality of data.

## Scope

This policy applies to all persons subject to organizational policies, irrespective of role or seniority. 

## Raison d'tre

Data seizures and forensic inspection of digital devices across borders are rare but on the rise. These present a very high risk to individuals with valuable digital assets. Following this SOP will mitigate the risk of data loss/compromise in most casual inspections. In worst-case scenario it will provide the best chance of safeguarding mission-critical data.

## Modus Operandi

Reduce attack surface by taking **only mission-critical data** across borders. To achieve this, personal data that is not mission-critical must be removed from the devices that will travel after being backed up to the cloud. That is why using a travel specific device can simplify things considerably.

Always prepare for the worst and hope for the best.

### Suitable Hardware

Only use **business-grade** or **enterprise-grade** laptops and phones. Consumer-grade devices should be avoided because they lack the security elements necessary to achieve baseline security and the performance and reliability to successfully navigate encryption/decryption and the necessary hardening that the task requires.

**Ideal Phones:** All **iPhones** currently supported by Apple, i.e. receiving security patches, **Samsung Galaxy** phones currently supported by Samsung. These phones are enterprise-grade. **Google Pixel** phones currently receiving security updates are also considered enterprise-grade, even if adoption is rare and availability isn't global.
These phones can be configured with hardened security settings to resist tampering somewhat, and keep data secure.

Apple iPhones, Samsung Galaxy and Google Pixel are on a league of their own when it comes to security.

The same cannot be said about other Android phones, even models included in the Android Enterprise Recommended list.

**Business-grade Laptops:** All **enterprise-grade** devices, plus Apple MacBook Air and Pro.

**Enterprise-grade Laptops:** Lenovo ThinkPad and ThinkBook all models, HP EliteBook and ZBook, Dell Pro/Pro Max in addition to a number of rugged devices by Panasonic, Dell, GTac  that should be avoided unless you're traveling for work and your work demands it (e.g. engineer working in construction) not because they lack anything but because they draw too much attention.

## Medium Risk vs High Risk

There is a huge difference between medium and high risk destinations. This policy does not include a list of destinations with a risk-rating. Instead, a framework is provided to evaluate risk on an individual basis, and for individuals to act accordingly to protect themselves and their data. This policy considers that the current possible minimum risk is **medium risk** and recommends whenever possible to follow the protocol for **high risk.**

## Personal risk

This policy mandates that all persons subjected to it must answer truthfully the following questionnaire in binary (Y/N):

- Are you, or have you ever been an activist, perceived by any government as an adversary?
- Have you published any content that is politically charged on social media.
- Are you objectively considered an influencer?
- Do you work in security of any kind, in particular cybersecurity?
- Would you, due to your appearance, look out of place in a corporate setting, like a bank?
- Are you a high-net worth individual?
- Do you carry over $10k in crypto? On hot or cold wallets?
- Do you carry material or is there anything about your person that can be considered immoral, pornographic, religiously proselytizing or politically subversive?
- Are you a journalist or a member of an NGO?
- Do you have visible tattoos, piercings and/or alterations in your person?

A single affirmative response to any of the questions above raises the risk profile from **medium risk** to **high risk** as per this policy and mandates strict adherence to the **high risk** security protocol.

## Destination Risk

This policy determines all destinations at minimum **medium risk** and raises the risk profile where one or more of the following conditions are met:

1. Government instability.
2. Widespread corruption.
3. Economic and social turmoil.
4. Authoritarianism.
5. Judicial <!--Expand this point-->

This policy recommends the use of either or both of the sources below to determine if the conditions above are met, in the absence of specialized intelligence.

### The Economist Intelligence Unit Democratic Index

This policy deems The Economist Intelligence Unit Democratic Index as a reliable source to determine the level of authoritarianism, and/or liberties warranted to individuals according to the judicial framework of the country. To obtain **The Economist Intelligence Unit Democratic Index**, request a copy of the latest one, visiting [EIU](https://www.eiu.com/n/campaigns/democracy-index-2024/).

### The Fragile State Index

The Fragile State Index is a valid source of intelligence as per this policy.

Click on [The Fragile State Index](https://fragilestatesindex.org/2025/02/18/https-fragilestatesindex-org-wp-content-uploads-2025-02-fsi-2024-report-a-world-adrift-2-pdf/) to download the latest -2024.





### Burner devices

For the purpose of this SOP a "burner" device is a travel-only device that will be sanitized when returned home. The device doesn't need to be destroyed after use, as a "genuine" burner used to be.

The devices used must meet security criteria listed before.

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



 