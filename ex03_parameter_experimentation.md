# Exercise 3: Parameter Experimentation

## Objective
Understand how parameters affect output diversity.

---

## Task 1: Temperature Tests

**Prompt:** "Write a short description of a coffee shop"

### Temperature = 0.2

**Response:**
The coffee shop is a small establishment that serves coffee and beverages. It has tables and chairs where customers can sit. The shop offers various types of coffee including espresso and cappuccino. It opens in the morning and closes in the evening.

---

### Temperature = 0.9

**Response:**
The cozy coffee shop features warm lighting and comfortable seating scattered throughout the space. Customers enjoy freshly brewed specialty drinks while the rich aroma of roasted beans fills the air. Friendly baristas craft each beverage with care, creating a welcoming atmosphere for both quick visits and longer stays.

---

## Task 2: Top-P Tests

**Temperature: 0.7 (constant)**
**Prompt:** "Write a short description of a coffee shop"

### Top-P = 0.5

**Response:**
A small coffee shop with wooden tables and chairs. The menu includes coffee, tea, and pastries. Customers can sit inside or take their drinks to go. The staff prepares fresh coffee throughout the day.

---

### Top-P = 1.0

**Response:**
This charming neighborhood coffee shop offers artisan beverages in a rustic-modern setting. Patrons gather around reclaimed wood tables, savoring handcrafted lattes while sunshine streams through large windows. The space buzzes with quiet conversation and the gentle hiss of the espresso machine.

---

## Summary

**Temperature findings:**
Lower temperature => plain, boring, factual and predictable. Higher temperature => more enriched and appealing text, more creative and interesting. 0.9 seems like a good constant good for most cases.

**Top-P findings:**
Lower top-p => narrower spectrum of word choices, boring, factual and safe. Higher top-p => broader variety in vocabulary. Contributes to creativity and raising the interest of the reader. The probability in choosing among many more words is clearly obvious in the second case.

