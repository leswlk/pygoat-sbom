# PyGoat-SBOM

As an addendum to the [PyGoat DevSecOps](https://github.com/leswlk/pygoat-github-actions)
project I've built, I created a workflow to generate an SBOM utilizing CycloneDX. Using OSV-Scanner, I can explore the vulnerabilities if needed.

## Tools used

 - Git CLI 
 - OSV-Scanner

## What is an SBOM?

An SBOM, or Software Bill of Materials, is a formal inventory of all the software components and their supply chain relationships used to build a piece of software. It could be thought of as an "ingredients list" of everything that's included on a food product, but in the case of software everything that's included would be vital components like libraries, versions, and licenses.

This is crucially important because this helps you know exactly what's inside your software, enables finding/fixing vulnerabilities faster, and meeting compliance requirements.

## Who should care about SBOMs in an organization?

Depending on the role/team within an organization, SBOMs has information for everyone.

### Developers
 - Provides easy visibility into included components
 - Dependency clarity to avoid bloat
 - Faster remediation when vulnerabilities occur
### Auditors
 - Traceability of components
 - Evidence of due diligence(helpful for compliance recertifications)
 - Verifiable documentation for builds
### Security Teams
 - Identify vulnerable libraries early
 - Verify license/compliance risks
 - Enforce policy on disallowed components
### Regulators
 - Compliance with EO 14028, NIST 800-218
 - Software transparency in procurement
 - Reduced risk in critical infrastructure

## Instructions

### Create CycloneDX Workflow
### Run Workflow
### Download SBOM
### View and investigate vulnerabilities
