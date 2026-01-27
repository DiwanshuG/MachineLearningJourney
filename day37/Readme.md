# Day 37 – Missing Value Imputation (Categorical Data)

Handling missing values in **categorical features** is crucial to avoid information loss and model errors.

## Common Approaches

### 1. Frequent Value Imputation
- Replace missing values with the **most frequent (mode)** category.
- Works well when missing data is **random and minimal**.
- Simple and widely used.

### 2. Adding a New Category (`"missing"`)
- Treat missing values as a **separate category**.
- Useful when missingness itself carries **information**.
- Helps models learn patterns from missing data.

**Key Idea:**  
Choose the method based on how and why the data is missing.

---  
*ML Journey – Day 37*
