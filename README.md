# SBT-DF203 Lab 7 — DNS Introduction and Traffic Analysis

## Overview

This repository contains my practical work for **SBT-DF203 — Basic Networking Skills for Digital Forensics, Lab 7: DNS Introduction and Traffic Analysis**.

The lab focused on understanding normal DNS behaviour, identifying the configured DNS resolver, generating and capturing DNS traffic, analysing DNS records, matching queries to responses, and correlating DNS answers with later network connections.

The practical was completed in a Kali Linux virtual machine using command-line tools and packet-capture utilities.

---

## Objectives

The main objectives of this lab were to:

- Identify the DNS resolver configured on the system.
- Use `dig` to query A, AAAA, MX and NS records.
- Capture a fresh DNS query with TShark.
- Preserve packet-capture evidence and calculate SHA-256 hashes.
- Extract DNS query and response fields.
- Match DNS queries and responses using transaction IDs and endpoint information.
- Analyse browser-generated DNS activity.
- Correlate DNS answers with later TCP connections.
- Review DNS activity within SMTP evidence.

---

## Tools Used

- Kali Linux
- VMware Workstation
- `dig`
- TShark
- Wireshark
- SHA-256 utilities
- Firefox Private Browsing

---

## Lab Environment

The configured DNS resolver identified during the practical was:

```text
192.168.45.2
