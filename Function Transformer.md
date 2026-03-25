What is Function Transformer?

FunctionTransformer is a utility in Scikit-Learn that allows you to apply a custom transformation function to your dataset inside an ML pipeline.

👉 In simple words:
It lets you use your own logic (function) as a preprocessing step.

Instead of only using built-in transformers (Scaler, Encoder), you can apply:

log transformation
square root
custom feature engineering
mathematical operations

inside a pipeline.

🧠 Why is Function Transformer Needed?

In real-world datasets:

Built-in transformers are not always enough
You need custom preprocessing logic
Feature engineering is project-specific
Pipelines require structured transformations

FunctionTransformer helps to:

✔ Apply custom preprocessing
✔ Keep pipeline clean
✔ Avoid manual data changes
✔ Maintain reproducibility
✔ Prevent data leakage

🔍 Types of Transformations Using Function Transformer

There are no fixed “types” in sklearn —
but conceptually, we use it for:

1️⃣ Mathematical Transformations

Example:

Log transform
Square root
Power transform

Use when:
Data is skewed.

2️⃣ Feature Engineering Transformations

Example:

Creating new features
Combining columns
Ratio features

Use when:
Domain knowledge needed.

3️⃣ Data Cleaning Transformations

Example:

Custom missing value logic
String processing
Custom mapping

Use when:
Standard methods not enough.

4️⃣ Statistical Transformations

Example:

Scaling via custom formula
Custom normalization

Use when:
Specific statistical assumptions exist.

⚙️ When to Use Function Transformer?

Use it when:

✔ You need custom preprocessing logic
✔ Built-in transformers are insufficient
✔ Working with pipelines
✔ Doing feature engineering
✔ Preparing production ML workflows

❗ When NOT to Use

Don’t use if:

StandardScaler already solves problem
OneHotEncoder sufficient
No custom logic needed

Because over-engineering makes pipeline complex.
