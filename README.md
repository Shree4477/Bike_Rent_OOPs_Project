🚲 Bike Rental System

A simple Python project that simulates a Bike Rental Service, allowing customers to rent and return bikes on a daily or weekly basis, with discounts for family rentals.

📋 Features :

📈 Rent Bikes based on available stock
🔁 Return Bikes and calculate bill
💸 Daily or Weekly rental options
🎯 Family Rental Promotion – 30% discount if renting 3 or more bikes for 5 or fewer days/weeks
🛡️ Basic validation for stock and rental requests

🛠 Technologies Used:

- Python 3
Object-Oriented Programming (OOP) Concepts
IPython Display (optional, used for clearing output in Jupyter Notebooks)

📂 Project Structure
- BikeRental (Parent class)
- Customer (Child class)
  - rentBike()
  - returnBike()
 
💻 How to Run the Project
1. Install Python if you haven't already.

2. Clone this repository or download the .py file.
Make sure you have contacts and any necessary methods like add_contact(), open_contact(), etc.
Run the Python file:
  - python bike_rental_system.py

📚 How the System Works
Customer provides:
    -Number of bikes to rent
    -Rental basis (daily or weekly)
    -Number of days/weeks they wish to rent
System checks:
    -If bikes requested are available
    -If input is valid
When returning:
    -Calculates total bill based on rental basis
    -Applies 30% discount if eligible

🔥 Family Rental Promotion
✅ If you rent 3 or more bikes
✅ And rent them for 5 or fewer days/weeks
➡️ You get a 30% discount on the total bill!

📷 Example Output:
Enter number of bikes you want to rent: 3
Enter rental basis (daily/weekly): daily
Enter number of days: 5

You rented 3 bikes.
Remaining stock: 97

-- After returning bikes --

Your total bill will be ₹1500
🎉 You are eligible for Family rental promotion of 30% discount!
Discount Amount: ₹450
Final Bill after Discount: ₹1050

🧹 Future Improvements
      -Add Hourly Rental Option
      -GUI (Graphical Interface) using Tkinter
      -Saving rental history into a database
      -Add penalty for late returns




