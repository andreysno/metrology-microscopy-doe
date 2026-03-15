# metrology-microscopy-doe

Microscopy Calibration Method & Statistical Robustness Analysis

## 🔬 Project Overview
This project presents a metrologically traceable calibration method for optical and digital microscopy. Developed as an Engineering Thesis, it integrates physical optics with advanced statistical tools to ensure measurement reliability in high-precision industrial environments.

## 🧠 Statistical & Engineering Core
- **Design of Experiments (DOE):** A $2^4$ full factorial design was executed to evaluate factors: Operator, Magnification, Backlight, and Incident Light.
- **Advanced Statistics:** Applied **Ryan-Joiner normality tests**, **Grubbs' test** for outliers, and **Box-Cox transformations** to satisfy ANOVA assumptions.
- **Metrological Traceability:** Developed uncertainty budgets under **GUM (ISO/IEC 17025)** guidelines, covering optical resolution limits, pixel size, and thermal expansion ($8 \times 10^{-6} \, ^\circ\text{C}^{-1}$ for glass patterns).

## 📊 Key Results
- **Significance:** ANOVA identified Magnification as the only factor with a p-value ($p = 0.0002$) below $\alpha = 0.05$.
- **Precision:** Higher magnification levels proved to be significantly more stable, with error margins below $\pm 0.002$ mm at 170X.
- **TUR Analysis:** Established operational limits for industrial tolerances (e.g., 34X is restricted to tolerances $\geq \pm 0.063$ mm).

## 📁 Repository Contents
- `Thesis_Report_ES.pdf`: Full technical document (Spanish).
- `/data_analysis`: Excel models for uncertainty budgets and Minitab output summaries.
- `/visuals`: ANOVA tables, Normal probability plots, and Uncertainty weight charts.
