# Masters Thesis - Adam Awadalla
## Developing an Open-source frequency domain modal analysis algorithm in Python

## Abstract
Structural dynamics relies on modal analysis to characterise vibratory behaviour in engineering systems, yet commercial software obscures underlying algorithms and imposes high licensing costs. This work aims to deliver a transparent, open-source alternative by implementing the polyreference least-squares complex frequency-domain estimator (pLSCF, PolyMAX) and a least-squares frequency-domain (LSFD) mode-shape routine in Python. Methods include a NumPy/SciPy - based architecture, rigorous unit- and integration-testing, PEP-8 documentation, and model-order-reduction via matrix truncation and singular-value decomposition to accelerate computation. Results on a ten-degree-of-freedom benchmark show natural frequencies and damping ratios within $9 \times 10^{-5} \%$  of analytical values; mode shapes reach modal-assurance-criterion scores $\geq$ 0.997. Computational time is reduced by up to two orders of magnitude relative to brute-force fitting, and accuracy is retained under 25 dB signal-to-noise conditions after peak-segmentation pre-processing. The study concludes that the presented library supplies a robust, high-performance, and freely accessible alternative to proprietary tools while providing a foundation for future enhancements such as MAC-based stability criteria, PolyMAX Plus noise handling, and an interactive graphical interface.


<p align="center">
  <a href="./main.pdf">
    <img src="https://img.shields.io/badge/View-PDF-red?style=for-the-badge">
  </a>
</p>
