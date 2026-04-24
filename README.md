## A. Executive Summary
Analysis of 500,000 products from the Open Food Facts database reveals that 
the snack market is overwhelmingly dominated by high-sugar, low-protein products. 
Across all major categories, fewer than X% of products meet a "High Protein + Low Sugar" 
profile (≥10g protein, ≤5g sugar per 100g). The biggest gap — the "Blue Ocean" — is 
in [Category], where only X% of products qualify. A new product targeting ≥Xg protein 
and <Xg sugar would face almost no direct competition in this segment.

## B. Project Links
- [**Notebook**](./sugar_trap_analysis.ipynb) 
- **Dashboard:** [Power BI public web link]
- **Presentation:** [Google Slides link]

## C. Technical Explanation
**Data Cleaning:** Dropped rows missing product_name, sugars_100g, or proteins_100g. 
Filtered out biologically impossible values (nutrients outside 0–100g/100g range, 
energy above 3,700 kJ/100g). Worked with the first 500,000 rows of the dataset to 
keep processing manageable.

**Candidate's Choice:** Added a Nutri-Score (A–E) distribution breakdown by category. 
This shows which categories are dominated by D/E-rated (unhealthy) products giving 
the client a retail shelf strategy, not just an R&D target.


## 🛑 CRITICAL: Pre-Submission Checklist

**Before you submit your form, you MUST complete this checklist.**

> ⚠️ **WARNING:** If you miss any of these items, your submission will be flagged as "Incomplete" and you will **NOT** be invited to an interview.
>
> **We do not accept "permission error" excuses. Test your links in Incognito Mode.**

### 1. Repository & Code Checks

- [ ] **My GitHub Repo is Public.** (Open the link in a Private/Incognito window to verify).
- [ ] **I have uploaded the `.ipynb` notebook file.**
- [ ] **I have ALSO uploaded an HTML or PDF export** of the notebook.
- [ ] **I have NOT uploaded the massive raw dataset.** (Use `.gitignore` or just don't commit the CSV).
- [ ] **My code uses Relative Paths.**

### 2. Deliverable Checks

- [ ] **My Dashboard link is publicly accessible.** (No login required).
- [ ] **My Presentation link is publicly accessible.** (Permissions set to "Anyone with the link can view").
- [ ] **I have updated this `README.md` file** with my Executive Summary and technical notes.

### 3. Completeness

- [ ] I have completed **User Stories 1-4**.
- [ ] I have completed the **"Candidate's Choice"** challenge and explained it in the README.

**✅ Only when you have checked every box above, proceed to the submission form.**

---
