# Verification

Verified on 11 November 2026 using an isolated Python 3.12 environment on macOS.

| Notebook | Executed code cells | Result |
|---|---:|---|
| Lab 3 classification | 23 | Passed |
| Lab 4 clustering | 25 | Passed |
| Lab 5 text mining | 20 | Passed |

All three notebooks were executed from fresh kernels in their respective lab folders. Outputs are saved in the notebooks. The direct package versions are recorded in `requirements-tested.txt`. Required NLTK resources were downloaded before execution with certificate verification enabled.

After execution, explanatory text in Labs 3 and 4 was reconciled with the resulting metrics and cluster profiles. No code was changed after these successful execution checks. Notebook structure, absence of error outputs, file sizes and package contents were checked before packaging.

These checks establish successful execution in the recorded environment. They do not establish production readiness, independent scientific replication or cross-platform compatibility. Lab 1 was not re-executed in this package. Lab 2 contains supporting data only, and no Power BI dashboard is claimed. GeoLife is reserved for a separate repository.
