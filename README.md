CP-Detection-DP
Dynamic Programming-based Circular Permutation Detection for Protein Sequences
![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
📖 Overview
This package implements a cyclic semi-global alignment dynamic programming algorithm for detecting circular permutation (CP) between two protein sequences. Circular permutation occurs when the N-terminal fragment of one protein is similar to the C-terminal fragment of another, and vice versa.
Key Features
✅ Cyclic semi-global alignment with affine gap penalties
✅ Time complexity O(2n²) — quadratic improvement over O(n⁴) methods
✅ Multiple substitution matrices: BLOSUM62, BLOSUM45, BLOSUM30
✅ Statistical validation: Z-score and empirical p-value (sequence shuffling)
✅ Command-line interface and Python API
✅ Batch processing for large-scale screening
✅ Open source (MIT License)
Algorithm Highlights
Feature	Our Method	Uliel et al. (1999)
Time Complexity	O(2n²)	O(n⁴)
Gap Penalty	Affine (realistic)	Linear
Breakpoint Enumeration	No (single DP)	Yes (explicit)
Statistical Validation	Yes (p-value, Z-score)	None
---
🔧 Installation
From GitHub
```bash
git clone https://github.com/yourusername/CP-Detection-DP.git
cd CP-Detection-DP
pip install -r requirements.txt
