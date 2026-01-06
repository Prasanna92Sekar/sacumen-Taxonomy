# Sacumen Cybersecurity Taxonomy

This repository defines a **vendor-neutral, ML-ready cybersecurity labeling taxonomy**
intended to be used by SacuNXT DataLab for labeling security events.

## Goals
- Provide consistent labels across security products
- Enable ML / AI training on security logs
- Remain independent of vendor schemas and SIEM formats

## What this repo IS
- A controlled vocabulary for security event labels
- A contract between raw data and labeled intelligence
- Versioned and governed taxonomy

## What this repo is NOT
- Not a SIEM schema
- Not detection rules
- Not product-specific logic

## Taxonomy Layers
- category — security domain (network, web, auth, etc.)
- event_type — what happened
- risk_level — severity / impact
- attack_type — inferred intent (optional)
- entity_type — target of the event

## Review Guidance (IMPORTANT)
Please focus review on:
- Naming consistency
- Practical usefulness
- Vendor neutrality
- Completeness of concepts (not size)

Do NOT focus on:
- Adding many labels
- Mapping every possible attack
- Implementation logic

## Status
Current version: SCIT-v0.1  
This version is intended for **internal review and iteration**.
