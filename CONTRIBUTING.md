# Contributing to redasm-dev/samples

This repository holds executable binaries used for regression testing.   
It is intentionally restrictive, every file must have a verified origin.

## Pull Requests
 
Pull requests are disabled.  
Binaries are committed by maintainers only.

## Submitting a Sample
 
To propose a new sample, open an issue using the **Sample Submission** template.  
**Issues that do not follow the template will be closed without review.**

## Acceptance Criteria
 
A sample will be accepted if it is:
- A crackme published by its author for public download and analysis
- Open source software compiled from a known source
- Authored by the submitter with source code provided

## Verification
 
- **Crackme / open-source**: provide a download link and SHA256 hash. The maintainer downloads and verifies the file before committing.
- **Authored**: provide the source code. The maintainer builds the binary independently. The submitter's binary is never used directly.

A sample will be rejected if:
- Its origin is unknown or unverifiable
- It is commercial or copyrighted software
- It does not pass verification
