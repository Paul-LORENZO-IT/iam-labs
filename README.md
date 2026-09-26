# 🔐 iam-labs

Hands-on labs on **Identity & Access Management (IAM)**, from Linux fundamentals up to the cloud.
I'm moving into infrastructure and security, with **IAM / cloud security** as my target.
Every lab is reproducible, documented, and includes what went wrong, because that's where I learn the most.

## 🗺️ Learning path and progress

| # | Lab | Topic | Tools | Status |
|---|-----|-------|-------|--------|
| 00 | [linux-fundamentals](./00-linux-fundamentals) | Users, groups, permissions, sudo, ACLs | Ubuntu | 🚧 |
| 01 | [directory](./01-directory) | Centralized directory, accounts and groups | OpenLDAP / Active Directory | 📅 |
| 02 | [authentication](./02-authentication) | Kerberos, TOTP MFA, password policy | Linux, Kerberos | 📅 |
| 03 | [sso-federation](./03-sso-federation) | SSO, OIDC and SAML | Keycloak | 📅 |
| 04 | [azure-entra-id](./04-azure-entra-id) | Users, groups, RBAC, Conditional Access | Microsoft Entra ID | 📅 |
| 05 | [aws-iam](./05-aws-iam) | Policies, roles, least privilege | AWS IAM | 📅 |
| 06 | [governance](./06-governance) | Joiner / mover / leaver, access reviews | Scripts, Entra ID | 📅 |
| 07 | [pam-secrets](./07-pam-secrets) | Privileged accounts, secrets management | Vault | 📅 |

✅ done · 🚧 in progress · 📅 planned

## 🧭 Why this order

1. **00 → 02: the basics.** Who is who, and how identity is proven.
2. **03: federation.** The core of IAM work.
3. **04 → 05: cloud.** Entra ID and AWS IAM, aligned with my certification path (AZ-104, then SC-300).
4. **06 → 07: governance and privileged access.** What sets IAM apart from classic administration.

## 🧪 Environment

- Virtualization: VirtualBox (Proxmox planned)
- Systems: Ubuntu Server, Windows Server (evaluation version)
- Cloud: disposable lab tenants and accounts only, never personal accounts

## 📐 Lab structure

Every lab follows the same template (see [`_templates/lab-template.md`](./_templates/lab-template.md)):

1. **Objective**: one sentence
2. **Prerequisites**: VMs, tools, versions
3. **Architecture**: diagram
4. **Steps**: reproducible commands and configs
5. **Verification**: how to prove it works
6. **Lessons learned / what broke**
7. **Certification link**
8. **Cleanup**: how to tear everything down

## 🔒 Repository security rules

- No secrets committed (passwords, keys, tokens): `.gitignore` and environment variables.
- Screenshots blurred or cropped (tenant, IDs, emails, IPs).
- Lab environments only, destroyed after use.

## 🎓 Background

Studying **Cybersecurity Expert – Secure Infrastructure Administrator** (French RNCP level 6, EQF 6), since October 2026.
Target path: IT support / infrastructure admin → cloud admin → **IAM / cloud security**.
Languages: French, English (B2), Spanish (B2). Targeting roles in Spain.

## 📫 Contact

[GitHub profile](https://github.com/Paul-LORENZO-IT) · [LinkedIn](https://linkedin.com/in/(https://www.linkedin.com/in/paul-lorenzo-0b5a2743a/?locale=fr-FR))
