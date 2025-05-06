# Ambyint Inc. - Data Scientist Assessment: Industrial System Analysis

## 1. Introduction

Welcome to the Data Scientist take-home assessment for Ambyint Inc. As a leader in AI-powered optimization for the Oil & Gas industry, we leverage data science to enhance production and operational efficiency.

This assessment allows you to demonstrate your data science skills by analyzing a simulated time-series dataset from an industrial system. We are interested in evaluating your analytical approach, technical execution, problem-solving abilities, critical thinking, and communication skills.

## 2. Objective

Analyze the provided time-series dataset simulating operational data from an industrial asset. This assessment has two parts:
    1. Developing a predictive model related to specific operational alerts.
    2. Performing a deeper, open-ended analysis focused on insights or optimization potential.

## 3. Dataset Overview

The necessary data files are located within the `datasets/` folder of this repository:

1.  **`train.csv`**: The primary dataset for training and analysis.
    *   **Content:** Contains approximately 80% of one year's simulated multi-sensor data. Includes various sensor readings, operational status (`Well_Operating_Status`), text notes (`Operational_Notes`), and a target `Monitoring_Alert` (0 = Normal, 1 = Alert Flagged).

2.  **`test.csv`**: A hold-out dataset for evaluating the predictive model from Part 1.
    *   **Content:** Contains the remaining ~20% of the data. **It does not include the `Monitoring_Alert` column.** All other columns and characteristics are consistent with the training data.

## 4. Assessment Tasks

Please structure your work clearly, addressing the following:

**Part 1: Monitoring Alert Prediction**

*   **Goal:** Using the **training dataset** (`datasets/train.csv`), develop a robust data-driven model to predict the `Monitoring_Alert` flag.
*   **Process:** Your analysis should cover standard data science workflow stages:
    *   Data exploration and understanding.
    *   Data preparation strategy.
    *   Feature engineering strategy.
    *   Model selection and implementation.
    *   Model evaluation.
    *   Interpretation of results.
*   Apply your trained model to the **test dataset** (`datasets/test.csv`) and include these predictions in your submission.

**Part 2: Open-Ended System Analysis & Optimization**

*   **Goal:** Leverage the **training dataset** and your insights to conduct a deeper analysis or propose a data-driven optimization related to the system's operation or health monitoring, going beyond Part 1. **You define the specific goal for this part.** (e.g., related to operational efficiency, sensor analysis, maintenance insights, risk characterization).
*   **Process:**
    *   Clearly state your chosen goal.
    *   Outline and implement an appropriate analytical approach, justifying your methodology.
    *   Present key findings and insights.
    *   Propose potential next steps or optimizations.
    *   Discuss the limitations and assumptions of your analysis.

## 5. Getting Started

1.  **Access the Code:** Fork this repository and clone your fork locally to begin working.
2.  **Isolate Your Work:** Create and work on a dedicated branch within your fork for this assessment.
3.  **Environment Setup:** Use a Python 3 virtual environment (`venv`, `conda`, etc.) for managing dependencies. Install the necessary libraries (e.g., pandas, scikit-learn, visualization tools, modeling libraries) required for your chosen approach.

## 6. Deliverables & Expectations

*   **Deliverable:** Your complete solution committed to Git (see Submission section). This should include:
    *   Code (e.g., Jupyter Notebooks, Python scripts).
    *   Clear documentation explaining your process, methodology, justifications, interpretations, and proposals for both Part 1 and Part 2.
*   **Focus:** Emphasis is on your analytical process, logical reasoning, justification of choices, handling of data complexities, critical thinking, and clear communication. **Final model performance metrics are secondary.**
*   **Time:** Part 1 typically requires core prediction skills (estimate 2-3 hours). Part 2 is open-ended (allocate time accordingly, e.g., 2-3 additional hours). Invest time wisely.
*   **Tools:** Use Python 3 and relevant data science libraries.

## 7. Evaluation Criteria (High-Level)

Your submission will be assessed based on:

*   **Problem Understanding & Data Handling:** Demonstrated ability to explore the data, understand its context/complexities, and apply appropriate handling techniques with justification.
*   **Methodology & Justification:** Soundness of the chosen strategies for data prep, feature engineering, modeling, and evaluation, supported by clear reasoning.
*   **Critical Thinking & Interpretation:** Depth of insights derived, ability to interpret results meaningfully, and critical assessment of limitations and assumptions.
*   **Communication:** Clarity, structure, and overall quality of your documentation and presentation within the submitted repository.
*   **(Part 2 Specific):** Clarity and relevance of the self-defined goal and the suitability of the approach taken.
*   **(Git Usage):** Basic use of version control with logical commits reflecting workflow stages.

## 8. Submission

1.  **Commit Your Work:** Commit all your completed work (code, notebooks, reports) with meaningful commit messages to the branch you created in your forked repository.
3.  **Share the Link:** Email the direct link to your specific branch within your forked repository to Mark Wiggins (`mark.wiggins@ambyint.com`).

Please ensure your repository link is accessible. Direct any essential clarifying questions regarding requirements to Mark Wiggins.

Thank you for participating. We look forward to reviewing your submission!