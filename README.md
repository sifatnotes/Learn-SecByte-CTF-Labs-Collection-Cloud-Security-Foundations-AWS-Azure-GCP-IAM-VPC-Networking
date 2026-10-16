# Learn-SecByte-CTF-Labs-Collection-Cloud-Security-Foundations-AWS-Azure-GCP-IAM-VPC-Networking
A curated collection of hands-on cloud security CTF labs covering Cloud IAM (AWS, Azure, GCP), VPC Networking, Container Security (Docker &amp; Kubernetes), Cloud Storage/Compute Security, and Logging &amp; Auditing from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a dedicated, searchable index of hands-on cloud security foundations, Identity & Access Management (AWS IAM, Azure AD/Entra ID, GCP IAM), Virtual Private Cloud (VPC) networking, container isolation (Docker & Kubernetes), compute and storage hardening, and centralized cloud auditing labs designed for cybersecurity students, CTF players, cloud security engineers, and DevOps/DevSecOps practitioners.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Establishing an unshakeable security baseline in cloud environments requires mastering core identity models, virtual network isolation, container runtime boundaries, and cloud logging. Hosted on [Learn SecByte](https://learn.secbyte.org/), this foundational cloud security collection provides practical, hands-on training across the essential building blocks of AWS, Azure, and Google Cloud Platform (GCP).

From auditing the Shared Responsibility Model and configuring least-privilege IAM policies across major cloud providers, to securing Virtual Private Clouds (VPCs), configuring Security Groups/Firewalls, hardening EC2/Azure VM/Compute Engine instances, securing S3/Blob storage, containerizing workloads safely with Docker and Kubernetes, and building centralized audit trails, these exercises establish core cloud defense competencies.

---

## Lab Collection & Index

Below is the complete, searchable index of all cloud foundations, IAM, networking, storage, compute, and container security challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Container Security: Docker & Kubernetes Deep Dive** | Container & Infrastructure Security | Container isolation mechanisms, Docker socket security, Kubernetes pod security standards (PSS), RBAC policies | [Access Lab](https://learn.secbyte.org/ctf/container-security-docker-kubernetes-deep-dive) |
| 2 | **Cloud Firewall & Security Groups** | Network Isolation & VPC Security | Stateful Security Groups, stateless Network ACLs (NACLs), GCP firewall rules, ingress/egress restriction | [Access Lab](https://learn.secbyte.org/ctf/cloud-firewall-and-security-groups) |
| 3 | **Virtual Private Cloud (VPC) Security Fundamentals: Cloud Networking** | Network Isolation & VPC Security | Subnetting (public vs. private), Internet Gateways, NAT Gateways, VPC Peering, Transit Gateways, Flow Logs | [Access Lab](https://learn.secbyte.org/ctf/virtual-private-cloud-vpc-security-fundamentals-cloud-networ) |
| 4 | **Google Cloud IAM: Secure, Abuse & Investigate Permissions** | Identity & Access Management (IAM) | GCP IAM roles (Primitive, Predefined, Custom), service accounts, Policy Intelligence, permission auditing | [Access Lab](https://learn.secbyte.org/ctf/google-cloud-iam-secure-abuse-investigate-permissions) |
| 5 | **Microsoft Azure Identity and Access Management** | Identity & Access Management (IAM) | Azure AD / Entra ID, Role-Based Access Control (RBAC), Service Principals, Managed Identities, PIM | [Access Lab](https://learn.secbyte.org/ctf/microsoft-azure-identity-and-access-management) |
| 6 | **AWS IAM Identity, Policy & Access Control Defense Lab** | Identity & Access Management (IAM) | AWS IAM JSON policy structure, explicit deny, trust relationships, Service Control Policies (SCPs), Access Analyzer | [Access Lab](https://learn.secbyte.org/ctf/aws-iam-identity-policy-access-control-defense-lab) |
| 7 | **Logging, Monitoring & Auditing Fundamentals** | Governance, Compute & Storage | CloudTrail, Azure Activity Log, GCP Cloud Audit Logs, CloudWatch, log integrity validation, SIEM export | [Access Lab](https://learn.secbyte.org/ctf/logging-monitoring-auditing-fundamentals) |
| 8 | **Compute Services Security: EC2, Azure VM & Compute Engine** | Governance, Compute & Storage | Instance metadata service (IMDSv2), SSH key management, disk encryption (KMS), security patches, VM hardening | [Access Lab](https://learn.secbyte.org/ctf/compute-services-security-ec2-azure-vm-compute-engine) |
| 9 | **Cloud Storage Security Fundamentals** | Governance, Compute & Storage | S3 bucket policies, Azure Blob access tiers, public access blocks, server-side encryption (SSE-KMS), CORS | [Access Lab](https://learn.secbyte.org/ctf/cloud-storage-security-fundamentals) |
| 10 | **Cloud Networking Fundamentals** | Network Isolation & VPC Security | OSI model mapping in cloud, DNS/Route 53, Load Balancers (ALB/NLB), VPN gateways, Direct Connect/ExpressRoute | [Access Lab](https://learn.secbyte.org/ctf/cloud-networking-fundamentals) |
| 11 | **IAM Fundamentals: From Authentication to Access Control** | Identity & Access Management (IAM) | Authentication vs. Authorization, MFA enforcement, federated identity, directory synchronization, SAML/OIDC | [Access Lab](https://learn.secbyte.org/ctf/iam-fundamentals-from-authentication-to-access-control) |
| 12 | **Shared Responsibility Model: Cloud Security Foundations** | Cloud Foundations & Core Models | CSP vs. customer security boundaries, IaaS vs. PaaS vs. SaaS risk profiles, compliance standards | [Access Lab](https://learn.secbyte.org/ctf/shared-responsibility-model-cloud-security-foundations) |

---

## Categories

### 1. Cloud Security Foundations & Identity (IAM)
Master cloud security ownership boundaries and implement least-privilege identity architectures across AWS, Azure, and Google Cloud.
- [Shared Responsibility Model: Cloud Security Foundations](https://learn.secbyte.org/ctf/shared-responsibility-model-cloud-security-foundations)
- [IAM Fundamentals: From Authentication to Access Control](https://learn.secbyte.org/ctf/iam-fundamentals-from-authentication-to-access-control)
- [AWS IAM Identity, Policy & Access Control Defense Lab](https://learn.secbyte.org/ctf/aws-iam-identity-policy-access-control-defense-lab)
- [Microsoft Azure Identity and Access Management](https://learn.secbyte.org/ctf/microsoft-azure-identity-and-access-management)
- [Google Cloud IAM: Secure, Abuse & Investigate Permissions](https://learn.secbyte.org/ctf/google-cloud-iam-secure-abuse-investigate-permissions)

### 2. Network Isolation, Firewalls & VPC Security
Architect private cloud networks, configure stateful/stateless traffic filters, and control data ingress and egress routes.
- [Cloud Networking Fundamentals](https://learn.secbyte.org/ctf/cloud-networking-fundamentals)
- [Virtual Private Cloud (VPC) Security Fundamentals: Cloud Networking](https://learn.secbyte.org/ctf/virtual-private-cloud-vpc-security-fundamentals-cloud-networ)
- [Cloud Firewall & Security Groups](https://learn.secbyte.org/ctf/cloud-firewall-and-security-groups)

### 3. Compute, Storage Hardening & Auditing
Hardening virtual machines, securing cloud object storage buckets, and establishing continuous logging across cloud control planes.
- [Cloud Storage Security Fundamentals](https://learn.secbyte.org/ctf/cloud-storage-security-fundamentals)
- [Compute Services Security: EC2, Azure VM & Compute Engine](https://learn.secbyte.org/ctf/compute-services-security-ec2-azure-vm-compute-engine)
- [Logging, Monitoring & Auditing Fundamentals](https://learn.secbyte.org/ctf/logging-monitoring-auditing-fundamentals)

### 4. Container & Infrastructure Security
Secure containerized workloads, audit Docker host configurations, and configure Kubernetes role-based access control.
- [Container Security: Docker & Kubernetes Deep Dive](https://learn.secbyte.org/ctf/container-security-docker-kubernetes-deep-dive)

---

## Learning Path

Follow this structured progression path to build foundational mastery in cloud architecture and cloud-native security engineering:

1. **Phase 1: Cloud Concepts & Identity Frameworks** — Understand governance boundaries and build least-privilege IAM policies:
   - [Shared Responsibility Model: Cloud Security Foundations](https://learn.secbyte.org/ctf/shared-responsibility-model-cloud-security-foundations)
   - [IAM Fundamentals: From Authentication to Access Control](https://learn.secbyte.org/ctf/iam-fundamentals-from-authentication-to-access-control)
   - [AWS IAM Identity, Policy & Access Control Defense Lab](https://learn.secbyte.org/ctf/aws-iam-identity-policy-access-control-defense-lab)
   - [Microsoft Azure Identity and Access Management](https://learn.secbyte.org/ctf/microsoft-azure-identity-and-access-management)
   - [Google Cloud IAM: Secure, Abuse & Investigate Permissions](https://learn.secbyte.org/ctf/google-cloud-iam-secure-abuse-investigate-permissions)

2. **Phase 2: Cloud Networking & Perimeter Defense** — Isolate workloads using VPC subnets, route tables, and firewalls:
   - [Cloud Networking Fundamentals](https://learn.secbyte.org/ctf/cloud-networking-fundamentals)
   - [Virtual Private Cloud (VPC) Security Fundamentals: Cloud Networking](https://learn.secbyte.org/ctf/virtual-private-cloud-vpc-security-fundamentals-cloud-networ)
   - [Cloud Firewall & Security Groups](https://learn.secbyte.org/ctf/cloud-firewall-and-security-groups)

3. **Phase 3: Compute, Storage & Audit Logging** — Hardened infrastructure resources and enable continuous monitoring:
   - [Cloud Storage Security Fundamentals](https://learn.secbyte.org/ctf/cloud-storage-security-fundamentals)
   - [Compute Services Security: EC2, Azure VM & Compute Engine](https://learn.secbyte.org/ctf/compute-services-security-ec2-azure-vm-compute-engine)
   - [Logging, Monitoring & Auditing Fundamentals](https://learn.secbyte.org/ctf/logging-monitoring-auditing-fundamentals)

4. **Phase 4: Container Runtime & Cluster Defense** — Apply runtime security and RBAC controls to Docker and Kubernetes:
   - [Container Security: Docker & Kubernetes Deep Dive](https://learn.secbyte.org/ctf/container-security-docker-kubernetes-deep-dive)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario directives and cloud environment specifications on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy cloud CLI utilities (AWS CLI, Azure CLI, gcloud SDK, kubectl, Docker CLI) inside an isolated testing workstation.
4. Audit IAM policies, verify VPC network flow logs, enforce bucket encryption, configure container security contexts, and retrieve target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute unauthorized network probes, privilege testing tools, or storage scraping scripts against production cloud accounts or third-party infrastructure.
