# ST5188 GAN-Augmented MRI Decision Support for Early AD/MCI Detection

Author：DING XINGTONG   QIN JIAYUE  CHAO ZICHENG  KAVYA DHANARAJ  LU JIAXIN

## Introduction

Early AD/MCI is hard to spot on routine structural MRI because changes are subtle and vary across scanners and sites, limiting early identification. This motivates decision support that highlights atypical anatomy and standardizes triage for closer review. We propose a GAN-assisted MRI workflow that (1) generates synthetic images to counter data scarcity/imbalance and (2) learns anomaly signals to augment a supervised classifier for early screening. 
The proposal centers on the clinical gap and stakeholder value, with methods kept at a high-level per course guidance.

## Studying Method
- GAN-based synthetic augmentation

- Unsupervised anomaly detection

- Supervised MRI classifier

- Anomaly–classifier fusion

- Decision-support triage

## Studying Value
This research delivers practical, near-term value for radiology and memory clinics. By standardizing triage across scanners and sites, it reduces inter-reader variability and flags subtle, early changes that are often missed on routine MRI. GAN-based synthetic augmentation eases data scarcity and class imbalance, improving model sensitivity without sacrificing specificity. 
Unsupervised anomaly maps provide case-level interpretability that clinicians can trust and act on, supporting transparent review and earlier intervention. Integrated into PACS, the workflow can shorten time-to-referral, enable more equitable screening, and generate harmonized data to accelerate future AD/MCI research.
