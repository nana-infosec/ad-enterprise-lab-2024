# ad-enterprise-lab-2024
Active Directory Enterprise Lab Deployment
# Active Directory Enterprise Lab (2024)

**Timeline:** 2024 – 2025  
**Tech:** Windows Server 2022, ADUC, DNS, DHCP, GPO, RSAT

## What I built
- Provisioned a domain with **OUs, users, and groups** aligned to an org chart.
- Configured **DNS/DHCP**; joined Windows 11 clients.
- Implemented **Group Policies** (password rules, workstation hardening).
- Documented **admin workflows** via RSAT.

## Why it matters
- Demonstrates identity & access management plus endpoint governance.
- Provides a repeatable lab environment for training/testing.

## Topology
- DC01 (AD DS, DNS, DHCP)  
- CL01–CL03 (Windows 11 Pro)

## Artifacts
- `/docs/ou-design.md`
- `/docs/gpo-baseline.md`
- `/docs/join-domain-checklist.md`
- `/assets/gpo-resultant-set.png`

## Lessons Learned
- Create OUs by **function** for cleaner GPO targeting.
- Test GPOs on a pilot OU before full rollout.
