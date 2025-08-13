# Discount Calculator

## Overview
This Python program calculates the final price of an item after applying a discount.  
If the discount is **20% or higher**, the discount is applied; otherwise, the original price is returned.

---

## Features
- Accepts original price and discount percentage from the user.
- Applies discount only if it's **≥ 20%**.
- Displays either the discounted price or the original price.
- Handles invalid inputs gracefully.

---

## Files
- **discount_calculator.py** — Main Python script containing:
  - `calculate_discount()` function
  - User input prompts and output messages

---

## How It Works
1. **Function**:
   ```python
   def calculate_discount(price, discount_percent):
       if discount_percent >= 20:
           discount_amount = (discount_percent / 100) * price
           return price - discount_amount
       else:
           return price
