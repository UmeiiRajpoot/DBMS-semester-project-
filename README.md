# DBMS-semester-project-

# Design a DATABASE
18. Campus Canteen with Meal Plans and QR Billing
Students subscribe to meal plans or pay-per-meal using QR codes. Admins track stock, daily
consumption, and vendor performance. Health inspectors audit quality, and results are logged.
Students can skip meals and donate them to needy peers. The system tracks leftovers and waste
management.

# ENTITIES AND ATTRIBUTES
1. STUDENT (Student_ID (Primary Key), Name, EmaiL, Enrollment_Date)
2. MEALPLAN (MealPlan_ID (Primary Key), Plan_Name, Duration, Price)
3. MEAL (Meal_ID (Primary Key), Meal_Name, Ingredients, Calories)
4. WASTE_LOGS (WasteLog_ID (Primary Key), Meal_ID (Foreign Key), Date, Quantity_Wasted)
5. VENDER (Vender_ID (Primary Key), Name, Contact_Info, Address)
6. INVENTORY (Inventory_ID (Primary Key), Item_Name, Quantity, Expiry_Date)
7. AUDIT_LOG (Log_ID (Primary Key), Vender_ID (Foreign Key), Inspector_ID (Foreign Key), Remarks)
8. INSPECTOR (Inspector_ID (Primary Key), Name, Contact)
9. TRANSACTION (TransactionID (Primary Key), Student_ID (Foreign Key), Data, Amount)
