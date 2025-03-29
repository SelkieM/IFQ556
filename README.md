# IFQ556
Object Orientated Programming
This C# console application calculates the total cost of fuel for a car based on user input. It demonstrates the use of methods, input validation, and basic conditional logic, all implemented within a single class as per assignment requirements.
💡 Features
Fuel Type Validation
Ensures the user enters a valid fuel type code in the format:

1 uppercase letter followed by 2 digits (e.g., E10, P95)

Invalid inputs like e10, Cs123, or 99X are rejected

User Input with Validation
Prompts user to enter:

✅ Number of litres filled

✅ Cost per litre (in dollars and cents)
Ensures all values are valid positive numbers

Total Cost Calculation
Calculates total cost using the formula:
Total Cost = Litres × Cost per Litre

🧠 Methods Used
public static bool IsValid(string id)
Validates fuel type string format

public static string InputFuelType()
Continuously prompts until a valid fuel type is entered

public static double GetPositiveNumber(string prompt)
Reusable method to accept and validate positive numeric input

public static double CalculateTotalCost(double litres, double costPerLitre)
Calculates the total cost of the fuel

