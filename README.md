# Computational Vaccine Design using Immunoinformatics

## Overview

This project focuses on identifying potential vaccine candidates using computational immunoinformatics tools. The SARS-CoV-2 membrane glycoprotein was analyzed for stability, antigenicity, and allergenicity.

## Data Source

* NCBI Protein Database
* Protein: SARS-CoV-2 membrane glycoprotein

## Tools Used

* ProtParam (ExPASy)
* VaxiJen 2.0
* AllerTOP v2.1

## Methodology

1. Retrieve protein sequence from NCBI
2. Analyze physicochemical properties (ProtParam)
3. Predict antigenicity (VaxiJen)
4. Predict allergenicity (AllerTOP)

## Results Summary

| Tool      | Result                    |
| --------- | ------------------------- |
| ProtParam | Stable protein            |
| VaxiJen   | Probable antigen (0.5102) |
| AllerTOP  | Non-allergen              |

## Conclusion

The protein demonstrates favorable properties including stability, antigenicity, and non-allergenicity, making it a potential vaccine candidate for further study.

## Repository Structure

* data/ → FASTA sequences
* results/ → Tool outputs
* README.md → Project documentation

