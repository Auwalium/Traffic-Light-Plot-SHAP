# Traffic-Light-Plot-SHAP
A Traffic Light Plot for visualizing SHAP explanations

# Traffic Light Plot

A Python package for generating visual "Traffic Light Plots", a standardised grid visualisation commonly used in systematic reviews and meta-analyses to display risk-of-bias judgements across multiple domains for individual studies.

---

## What is a Traffic Light Plot?

A **Traffic Light Plot** visually presents quality assessments or risk-of-bias judgements (such as Cochrane's RoB 2 or ROBINS-I tools) across a set of studies. It uses a colour-coded matrix:

* **Green (Low Risk / Pass):** Meets quality criteria.
* **Red (High Risk / Fail):** Fails quality criteria or high risk of bias.

### Why is it Useful?

* **Instant Scannability:** Converts dense tabular risk-of-bias data into an intuitive visual format.
* **Cross-Study Comparisons:** Allows reviewers and readers to quickly identify systemic weaknesses across a body of literature.
* **Publication Ready:** Generates high-resolution figures optimized for academic manuscripts.


## Installation

Clone the repository and install the required dependencies:

```bash
git clone [https://github.com/Auwalium/Traffic-Light-Plot-SHAP.git](https://github.com/Auwalium/Traffic-Light-Plot-SHAP.git)
cd Traffic-Light-Plot-SHAP
pip install -r requirements.txt
