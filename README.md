# Inventory-of-phones
# Phone Store Application

This Python application simulates a simple phone purchase process, incorporating object-oriented programming (OOP) concepts and data handling from an Excel file.

## Key Features:

Models Phone Inventory: The Smartphone class represents individual phones with attributes like model, price, tax, delivery fees, and a discount method.
Loads Data from Excel: The PhoneStore class reads phone data from an Excel file using the openpyxl library.
Handles User Interaction: The application prompts the user for their desired phone model and age, applies discounts based on age and discount codes, and calculates the final price.
Applies Discounts: The apply_discount method effectively reduces the price of a Smartphone object based on a class-level discount percentage.
