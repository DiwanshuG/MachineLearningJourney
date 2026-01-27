## Missing Value Imputation – Key Techniques (Day 38)

### 1) Automatically Select Imputation Technique
- The imputation method is chosen **based on data behavior**.
- Distribution, missing percentage, and relationship with target are analyzed.
- Helps avoid manual bias and improves model robustness.

---

### 2) Missing Indicator
- A new binary feature is created:
  - `1` → value was missing  
  - `0` → value was present
- Captures information carried by missingness.
- Often used along with another imputation method.

---

### 3) Random Sample Imputation
- Missing values are replaced with **randomly sampled existing values** from the same feature.
- Preserves the original data distribution.
- Useful when missing values are not very frequent.

---

**Goal:** Handle missing values without losing important information or distorting data patterns.
