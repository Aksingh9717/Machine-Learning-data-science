🔹 What is One Hot Encoding?

One Hot Encoding is a data preprocessing technique used to convert categorical variables into a numerical format that machine learning models can understand.

It creates new binary columns for each unique category in the feature.

Example:

Color → Red, Blue, Green

After One Hot Encoding:

Red → 1 0 0
Blue → 0 1 0
Green → 0 0 1

🔹 Why One Hot Encoding is Important

Machine learning models cannot interpret text-based categorical values directly.
One Hot Encoding helps represent categorical data without introducing any ranking or order.

This improves:

Model accuracy
Feature representation
Learning performance
🔹 When to Use One Hot Encoding
When categorical data has no natural order (Nominal data)
When working with linear models, tree models, clustering etc.
When avoiding bias from label encoding
