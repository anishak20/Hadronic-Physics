# |V_ub| Determination from the Semileptonic B -> pi l nu Decays

This project was carried out during REYES 2023 under the guidance of Dr. Sergi Gonzàlez-Solís.

## Objective

To extract the CKM matrix element |V_ub| using semileptonic B0 -> pi- l+ nu decays by applying theoretical modeling and chi-square fitting to experimental data.

## Prerequisites

To run this project locally, ensure you have the following Python libraries installed:

```bash
pip install numpy pandas matplotlib scipy astropy
```

## Introduction

The B meson is a bound state consisting of a bottom (b) quark and either an up or down quark. It is an unstable, heavy meson that decays via the weak interaction, making it a valuable probe for studying flavor physics and the elements of the CKM matrix.

Our interest lies in charged current weak interactions, which have their flavor structure encoded in the CKM matrix. The element V\_ub connects an up-type quark to a bottom-type quark. However, the Standard Model does not predict specific values for these elements—they must be determined experimentally. Of all the CKM parameters, |V\_ub| is one of the least precisely known, and its accurate extraction helps in testing the consistency of the Standard Model.

## Project Workflow

The full analysis is implemented in the Jupyter notebook `vub_determination_reyes.ipynb`. The steps followed in the project are:

1. Model the hadronic form factor f\_+(q^2) using two approaches: a single pole model and a multi-pole model.
2. Define the theoretical branching ratio expression as a function of q^2 and |V\_ub|.
3. Import experimental data of q^2 vs dB/dq^2 for fitting.
4. Fit the data using a nonlinear least squares chi-square method to extract the best-fit value of |V\_ub|.
5. Compare both models and determine which provides the better agreement with the data.

## Conclusion

Model 2 (multi-pole) provides a better fit to the experimental data compared to Model 1. The project demonstrates a methodology for extracting flavor physics parameters from decay data using theoretical modeling and numerical optimization.

## Contact

For queries, feel free to reach out:
Email: [khatri.anisha20@gmail.com](mailto:khatri.anisha20@gmail.com)
LinkedIn: [https://linkedin.com/in/AnishaKhatri](https://linkedin.com/in/AnishaKhatri)

