# BANNER BATTLE

### Project Overview

This project explores whether different banner ad types—**sneakers** vs. **accessories**—have a measurable impact on **sales conversions** among desktop users during **May 2019**. Using real-world customer data, we apply A/B testing principles to determine if banner design can influence purchase behavior.

This isn’t a theoretical exercise—it’s a practical test of how design and marketing choices translate into business outcomes.

### Research Question

**Is there a significant difference in sales conversions between desktop customers who saw the sneakers banner and those who saw the accessories banner during May 2019?**

Answering this allows marketers and product teams to:

* Optimize digital ad performance
* Design smarter landing experiences
* Avoid costly assumptions

### Test Design

#### Target Variable

* 1: Customer saw the ad **and converted**
* 0: Customer saw the ad but **did not convert**

#### Sample Selection

* Device: **Desktop only**
* Period: **May 2019**
* Exposure: Banner shown was either *sneakers* or *accessories*

### Statistical Method

A **Chi-Square Test of Independence** was used to compare conversion outcomes between the two banner groups. This evaluates whether observed differences are statistically significant or just due to chance.

### Key Features of the Analysis

* Binary classification of customer conversion
* Clean construction of a contingency table
* Application of Chi-Square hypothesis testing
* Thoughtful interpretation of both statistical results and business value

### Results & Interpretation

I evaluated:

* Whether there was a statistically significant difference in conversions
* How meaningful the difference would be in a real-world marketing context

The notebook includes a detailed walkthrough of the process, complete with commentary on test setup, assumptions, and actionable implications.

### Setup Instructions

To run this notebook on your local machine:

#### 1. Clone or download the repository

If you're starting from this notebook file only, place it in your preferred working directory.

#### 2. Create a Python environment

We recommend using **Anaconda** or **venv** for environment management.

```bash
# Create and activate a virtual environment (optional)
python -m venv abtest-env
source abtest-env/bin/activate  # or abtest-env\Scripts\activate on Windows
```

#### 3. Install required packages

Use `pip` to install dependencies:

```bash
pip install pandas scipy matplotlib jupyter
```

#### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook file (A_B_Testing_2.ipynb) from the Jupyter dashboard.

### Why This Matters

This project shows how A/B testing applies beyond tech giants—it’s a crucial tool for any business seeking clarity in decision-making. Marketing assumptions are tested, not trusted. Design ideas are validated, not just shipped.

If your brand lives online, experiments like these are your sharpest edge.
