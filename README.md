Fuzzy Labeled Private Set Intersection (FLPSI) for Privacy-Preserving Biometric Matching

This project demonstrates adaptive thresholding in Fuzzy Labeled Private Set Intersection (FLPSI) to enable privacy-preserving biometric searches. It addresses the challenge of private querying for noisy biometric data (e.g., face recognition) against a private database. The implementation allows users to securely find approximate matches within a database, ensuring privacy and accuracy through noise resilience techniques.

Project Overview

Biometrics data, commonly used in surveillance, poses unique privacy challenges. This project simulates a FLPSI protocol that matches biometric queries under controlled noise, demonstrating efficient and private biometric search.

Key Features

Privacy-Preserving Matching: Uses FLPSI to maintain privacy while finding matches within a private database.
Noise Resilience: Adapts to noisy biometric data, adjusting thresholds to improve match rates.
Efficiency: Optimized for fast query response times even with large datasets, and tested over WAN/LAN environments.
Getting Started

Prerequisites:

Python 3.x
Jupyter Notebook
Required Python libraries (see requirements.txt)

Setup: 

Clone the repository, install dependencies, and open the notebook for step-by-step execution.
Running the Code: The Jupyter Notebook provides the implementation details, code, and sample data. Execute each cell to simulate the FLPSI protocol and visualize results.

Project Files

FLPSI_Notebook.ipynb: Main notebook with code, explanations, and visualizations.
sample_data/: Sample biometric data with simulated noise.
README.md: Project overview and setup guide.

Results

Average Runtime per Query: 0.2773 seconds
Average Matches per Query: Demonstrates both successful matches and potential edge cases.

Project Limitations

Noise Threshold: Higher noise levels may lead to false matches, requiring future tuning.
Scalability: Efficient with large datasets, but further optimization can improve performance.

Future Research

Refining threshold parameters for specific biometric datasets.
Exploring additional privacy layers for enhanced data security.
