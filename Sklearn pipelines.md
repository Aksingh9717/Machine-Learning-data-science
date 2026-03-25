What is a Pipeline?

A Pipeline in Scikit-Learn is a sequence of data preprocessing and modeling steps that are executed in order.

It helps combine multiple steps like:

Feature scaling
Encoding
Transformation
Model training

into a single workflow.

🔹 Why is Pipeline Important?

In real-world machine learning projects:

Data preprocessing must be consistent
Training and testing transformations must be identical
Manual preprocessing increases risk of errors
Code becomes messy without structured workflows

Using Pipelines helps:

✔ Prevent data leakage
✔ Maintain clean and reproducible code
✔ Automate ML workflows
✔ Simplify model deployment
✔ Improve experiment tracking

🔹 Example Workflow

Dataset contains:

Numerical features → scaling
Categorical features → encoding
Final step → model training

Pipeline ensures all steps run in correct order automatically.
