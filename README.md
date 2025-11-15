# Shopify Coding Exercise / Cleaned Product Template

This submission contains my refactored version of the provided `product.messy.liquid` file.  
The goal was to improve readability, structure, and Liquid correctness while preserving all existing functionality.

---

## Files Included

### 1. **product.cleaned.liquid**
A fully refactored version of the original template.  
Key improvements include:
- Standardized indentation and spacing  
- Grouped and clarified variable assignments  
- Replaced deprecated `{% style %}` tag with a valid `<style>` block  
- Consolidated variant logic into a cleaner `{% liquid %}` block  
- Removed duplicate `product-form` render  
- Ensured JSON output uses the Liquid `| json` filter for valid JavaScript  
- Cleaned and structured the badges logic without altering behavior  
- Maintained all original business rules, date logic, and pricing functionality  

### 2. **NOTES.md**
A detailed breakdown of all changes made, including:
- Line-by-line cleanup notes  
- Areas of improved maintainability  
- Clarifications of logic preserved from the original  
- One optional suggestion for modularizing repeated blocks in a real project  

---

## Approach

My focus was on:
- Improving readability without introducing new features  
- Keeping the template semantically structured and easy to follow  
- Ensuring the Liquid syntax fully validates  
- Maintaining the behavior, output, and user-facing logic of the original  

I treated this as if it were part of a production Shopify theme with the goal of making future modifications easier, clearer, and safer.

---

## Optional Improvement (Not Implemented)

If this were part of a larger theme refactor, I would consider extracting the pricing block and badges block into reusable snippets for maintainability.  
This is noted but intentionally not implemented to comply with the exercise requirements.

---

## Cleaned by
**Nathalia Mora**  
