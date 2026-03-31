The Dietician: BMR & Meal Planner
A desktop application built with Python and Tkinter that calculates a user's Basal Metabolic Rate (BMR) and Total Daily Energy Expenditure (TDEE) to suggest a personalized daily meal plan.

---

# Features
BMR Calculation: Uses the Harris-Benedict Equation to calculate caloric needs based on gender, weight, height, and age.

Activity Adjustment: Adjusts calorie goals based on five different activity levels (from sedentary to super active).

Dynamic Meal Planning: Generates a randomized meal plan (Breakfast, Lunch, Dinner, and Snacks) categorized by the user's specific caloric tier:

Under 1,500 kcal

1,500 - 1,800 kcal

1,800 - 2,200 kcal

Over 2,200 kcal

User-Friendly GUI: Built with Python’s tkinter library for a simple, functional interface.

---

# Requirements
Python 3.2

Tkinter (usually included with standard Python installations)

---

# How it Works
The application calculates calories using the following formulas:

For Men:

BMR = 66.0 + (13.7*weight in kg) + (5.0*hight in cm) - (6.8*age in years)

For Women: 

BMR = 655.0 + (9.6*weight in kg) + (1.8*hight in cm) - (4.7*age in years)

---

# Meal Categories
The app selects items from pre-defined lists of:

Proteins: Yogurt, Meat, Fish, Eggs, Tofu.

Grains: Oats, Bread, Potatoes, Tortillas.

Fruits & Vegetables: Berries, Apples, Leafy Greens, etc.

Taste Enhancers: Healthy fats like Avocado, Nuts, and Olive Oil.
