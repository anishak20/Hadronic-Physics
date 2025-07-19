# $|V_{ub}|$ Determination from the Semileptonic $B\to\pi\ell\nu_{\ell}$ Decays

This project aims to extract the CKM matrix element \( |V_{ub}| \) using semileptonic \( B^0 \rightarrow \pi^- \ell^+ \nu_\ell \) decays, through a theoretical model and chi-square fitting of experimental data.

## Introduction

The **B meson** is a bound state consisting of a bottom (b) quark and either an up or down quark. It is an unstable, heavy meson that decays via the **weak interaction**, making it a valuable probe for studying flavor physics and the elements of the CKM matrix. In this project, we observe the **semileptonic decay** of the \( B^0 \) meson to extract the parameter \( |V_{ub}| \).

Our interest lies in charged current weak interactions, which have their flavor structure encoded in the \( V_{\text{CKM}} \) matrix ([reference](https://rb.gy/w9ezn)). An element \( V_{ij} \) of this matrix connects an up-type quark of the \( i \)-th generation with a down-type quark of the \( j \)-th generation. However, \( V_{ij} \) cannot be predicted within the Standard Model and must be determined experimentally.

We specifically focus on extracting \( |V_{ub}| \), which has the largest uncertainty among the unitarity triangle parameters. For instance, purely leptonic \( B \)-meson decay measurements gave:
- \( |V_{ub}|^{\text{BaBar}} = 5.26(12)(73) \times 10^{-3} \)
- \( |V_{ub}|^{\text{Belle}} = 3.75(8)(47) \times 10^{-3} \)

The significant discrepancy between these measurements motivates the use of **semileptonic charmless decays**, particularly \( B^0 \rightarrow \pi^- \ell^+ \nu \), for a more precise determination.

## Theoretical Framework

Semileptonic decays depend on hadronic form factors \( f_+ \) and \( f_0 \). Two models are considered:

**Model 1: Single Pole/Resonance**
\[
f_{+}(q^2) = \frac{f_{+}(0)}{1 - q^2/m_{B^*}^2}
\]

**Model 2: Multi-Pole Model**
\[
f_{+}(q^2) = \frac{f_{+}(0)}{(1 - q^2/m_{B^*}^2)(1 - \alpha q^2/m_{B^*}^2)}
\]
where \( \alpha = 0.54(17) \)

### Branching Ratio Expression

To determine \( |V_{ub}| \), we use the expression:

\[
BR = \frac{1}{\Gamma_{B^0}} \int_0^{(m_B - m_\pi)^2} \mathrm{d}q^2 \cdot \frac{G_F^2 |V_{ub}|^2 \lambda^{1/2}(m_B^2, m_\pi^2, q^2)}{128 \pi^3 m_B^3 q^2}
\left(1 - \frac{m_\ell^2}{q^2} \right)^2 \left[ \frac{2 q^2}{3} \lambda(m_B^2, m_\pi^2, q^2) \left(1 + \frac{m_\ell^2}{2 q^2} \right) |f_+(q^2)|^2 \right]
\]

### Constants Used

- \( BR = 1.50(6) \times 10^{-4} \)
- \( \Gamma_{B^0} = 4.33 \times 10^{-13} \,\text{GeV} \)
- \( m_B = 5.27966 \,\text{GeV} \)
- \( m_\pi = 0.13957 \,\text{GeV} \)
- \( G_F = 1.166 \times 10^{-5} \)
- \( m_e = 0.511 \,\text{MeV} \)
- \( f_+(0) = 0.261(23) \)
- \( m_{B^*} = 5.324 \,\text{GeV} \)
- \( \lambda(x,y,z) = x^2 + y^2 + z^2 - 2(xy + xz + yz) \)

## Fitting and Extraction

We fit the theoretical differential branching ratio:

\[
\frac{dB}{dq^2} = \frac{G_F^2 |V_{ub}|^2 \lambda^{1/2}(m_B^2, m_\pi^2, q^2)}{\Gamma_{B^0} 128 \pi^3 m_B^3 q^2}
\left(1 - \frac{m_\ell^2}{q^2} \right)^2 \left[ \frac{2 q^2}{3} \lambda(m_B^2, m_\pi^2, q^2) \left(1 + \frac{m_\ell^2}{2 q^2} \right) |f_+(q^2)|^2 \right]
\]

to the experimental data using nonlinear least squares optimization. The Chi-square function minimized is:

\[
\chi^2 = \sum_i \left( \frac{\Delta_i^{\text{data}}}{\sigma_i^{\text{data}}} \right)^2, \quad
\Delta_i^{\text{data}} = \left( \frac{dB}{dq^2} \right)_i^{\text{data}} - \left( \frac{dB}{dq^2} \right)_i^{\text{theory}}
\]

### Conclusion

The chi-square fit shows that **Model 2 (multi-pole)** better reproduces the experimental data, making it a more reliable model for estimating \( |V_{ub}| \). This project demonstrates how precise flavor parameters can be extracted using decay data and theoretical modeling in the context of the Standard Model.

## Contact

For queries, contact:  
📧 **khatri.anisha20@gmail.com**  
🔗 [LinkedIn](https://linkedin.com/AnishaKhatri)
