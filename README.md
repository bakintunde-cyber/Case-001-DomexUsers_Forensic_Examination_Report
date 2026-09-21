# Case-001-DomexUsers_Forensic_Examination_Report

## Digital Forensics Case Investigation

This repository documents a digital forensic examination of a Windows forensic image. The investigation focuses on identifying and correlating user-account information, web-history artifacts, file-system evidence, and other system artifacts while maintaining evidence integrity and documenting the examination process.

---

## Case Overview

**Case ID:** CASE-001  
**Case Name:** DomexUsers Forensic Examination  
**Examination Type:** Digital Forensics / Computer Forensics  
**Evidence Type:** Windows forensic disk image  
**Primary Objective:** Identify, examine, and correlate relevant artifacts recovered from the forensic image.

---

## Investigation Objectives

The objectives of this examination were to:

- Verify the integrity of the acquired forensic evidence.
- Identify user accounts present on the examined system.
- Examine web-history artifacts.
- Identify relevant files and file-system artifacts.
- Examine deleted-file evidence where applicable.
- Establish timelines from available forensic artifacts.
- Correlate artifacts across the forensic image.
- Document findings using screenshots and forensic notes.
- Preserve a clear and reproducible examination record.

---

## Tools Used

The investigation used forensic and system-analysis tools to examine and document the evidence.

### Forensic Tools

- Autopsy
- FTK Imager
- PowerShell

### Analysis Techniques

- Hash verification
- File-system examination
- Windows user-account analysis
- Web-history analysis
- Deleted-file examination
- Timeline analysis
- Artifact correlation

---

## Evidence Integrity

Before analysis, the evidence was subjected to hash verification to confirm that the forensic evidence being examined matched the expected hash value.

Hash verification is an important forensic procedure because it helps demonstrate that the evidence has not been altered during acquisition, transfer, or examination.

**Hash verification status:** Verified

Evidence-integrity screenshots are located in:

`Screenshots/`

---

## Evidence Examined

The examination included several categories of artifacts.

### 1. User Accounts

The forensic image contained the following Windows user accounts:

- Administrator
- domex1
- domex2

The presence of a user account alone does not establish that the account was actively used during the relevant period. Additional artifacts must be correlated before drawing conclusions about user activity.

---

### 2. Web History

Web-history artifacts associated with the `domex2` user account were examined.

One identified artifact contained a URL associated with Microsoft's Live.com account/sign-in services.

**Observed artifact date/time:**

`2008-10-30 02:43:25 EDT`

The web-history artifact was documented and preserved as part of the evidence-correlation process.

---

### 3. File-System Evidence

File-system artifacts were examined to identify relevant files, directories, metadata, and other information that could contribute to the investigation.

Where applicable, file attributes and timestamps were reviewed to assist with timeline and activity analysis.

---

### 4. Deleted Files

Deleted-file artifacts were examined to determine whether recoverable information was present within the forensic image.

Recovered or identified deleted-file evidence was documented with supporting screenshots.

---

### 5. Timeline Analysis

Relevant timestamps were examined to help establish relationships between artifacts and identify potentially related system activity.

Timeline evidence was considered together with other artifacts rather than being interpreted in isolation.

---

## Evidence Correlation

The investigation uses artifact correlation to connect information from multiple sources.


User Account
     ↓
Web History
     ↓
File-System Artifacts
     ↓
Timestamps
     ↓
Deleted Files
     ↓
Evidence Correlation
