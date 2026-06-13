# Contributing to redasm-dev/samples

This repository holds executable binaries used for regression testing, for safety reasons it's intentionally restrictive: <u>every file must have a verified origin</u>.  
Pull requests are disabled, binaries are committed by maintainers only.  

## How to submit a Sample
 
To propose a new sample, open an issue using the **Sample Submission** template.  
**Keep in mind that issues that do not follow the template will be closed without review.**

## Sample evaluation
 
**ACCEPTED** if:
- a crackme published by its author for public download and analysis
- open source software compiled from a known source
- authored by the submitter with source code provided (see below)

**REJECTED** if:
- it's commercial or copyrighted software
- its origin is unknown or unverifiable
- it does not pass verification

## Verification
 
- **Crackme / Open Source**: provide a download link and SHA256 hash. The maintainer will evaluate the file before committing.
- **Authored**: provide the source code. The maintainer will compile the binary.

