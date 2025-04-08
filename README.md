# BloodHound Example Data

This repository provides sample datasets for testing BloodHound without needing to perform live SharpHound or AzureHound collections. These datasets are ideal for learning, demonstrations, or practice in lab environments.

---

## AD Example Data

**Download:**  
[ad_example_data.zip](https://github.com/Artifice-Sec/Bloodhound-Sample-Data/raw/refs/heads/main/ad_example_data.zip)

This Active Directory example environment includes:
- 3 collected domains with trust relationships between them
- Additional, visible, trusted domains without collections
- Coverage for local permissions (including group memberships and ACLs)
- Multiple Active Directory Certificate Services (ADCS) escalation paths

---

## Azure Example Data

**Download:**  
[azurehound_example.zip](https://github.com/Artifice-Sec/Bloodhound-Sample-Data/raw/refs/heads/main/azurehound_example.zip)

This Azure example environment includes:
- Full collection of an Azure Active Directory (AzureAD) environment
- Support for user-sync hybrid paths when ingested alongside the example AD data

---

> ⚡ These sample datasets are provided for training, educational purposes, and testing BloodHound capabilities.  
> ⚡ No live Active Directory or Azure environments are needed to work with these files.
