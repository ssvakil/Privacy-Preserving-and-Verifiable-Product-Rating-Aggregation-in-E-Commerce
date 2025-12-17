# Privacy-Preserving-and-Verifiable-Product-Rating-Aggregation-in-E-Commerce
Privacy-Preserving and Verifiable Product Rating Aggregation in E-Commerce Using Threshold Homomorphic Encryption with Distributed Key Generation
# Formal Verification of Five Security Protocols Using ProVerif

## Project Overview
This repository presents the formal verification of five cryptographic security protocols using ProVerif, an automated tool for analysing protocols in the symbolic model (Dolev-Yao model).

Each protocol has been evaluated for essential security properties, including:
- Secrecy (confidentiality of sensitive data)
- Authentication (correct correspondence between participants)
- Resistance to potential attacks

It should be noted that the outputs from the ProVerif verification for all protocols confirm that no attacks were successful, and the desired security properties were preserved in each case.

**Objective**: To demonstrate the security of these protocols through automated formal verification.

**Tool Used**: ProVerif (version 2.x) – [Official Website](http://prosecco.gforge.inria.fr/personal/bblanche/proverif/)

## Repository Structure
The repository is organised into separate folders for each protocol:

- `/protocol1/` : Materials for Protocol 1
  - `protocol1.pv` : ProVerif input model (plain text file)
  - `protocol1.out` : ProVerif verification output (text file containing results)
  - `protocol1_notebook.html` or exported Jupyter Notebook output (for static viewing)

- `/protocol2/` : Materials for Protocol 2
- `/protocol3/` : Materials for Protocol 3
- `/protocol4/` : Materials for Protocol 4
- `/protocol5/` : Materials for Protocol 5

- `main_analysis.ipynb` : Main Jupyter Notebook providing an overview, summary of results, and optional Python-based analysis.

## Summary of Verification Results

| Protocol     | Secrecy            | Authentication     | Attack Found? | Overall Outcome          |
|--------------|--------------------|--------------------|---------------|--------------------------|
| Protocol 1   | Verified ✓        | Verified ✓        | No            | Secure                   |
| Protocol 2   | Verified ✓        | Verified ✓        | No            | Secure                   |
| Protocol 3   | Verified ✓        | Verified ✓        | No            | Secure                   |
| Protocol 4   | Verified ✓        | Verified ✓        | No            | Secure                   |
| Protocol 5   | Verified ✓        | Verified ✓        | No            | Secure                   |

> Note: In all cases, ProVerif was unable to identify any attack, confirming that the specified security properties hold.

## Reproducing the Results
The verification results are pre-computed and included in the repository. To reproduce them (optional):


1. Download and install ProVerif from the official website.
2. Navigate to the relevant protocol folder and execute:
