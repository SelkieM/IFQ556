# IFQ556 

Object Orientated Programming

TWO PROJECTS DEMONSTRATING OBJECT ORIENTATED PROGRAMMING IN C#

PROBLEM SOLVING TASK: 

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
public static bool IsValid(string id) - Validates fuel type string format
public static string InputFuelType() - Continuously prompts until a valid fuel type is entered
public static double GetPositiveNumber(string prompt) - Reusable method to accept and validate positive numeric input
public static double CalculateTotalCost(double litres, double costPerLitre) - Calculates the total cost of the fuel


PROGRAMMING ASSIGNMNET: 

This C# console application simulates a basic bookstore system. It allows users to input book details, categorize books, and filter by category. The solution is built across a single project using a Program class and a custom Book class, with a strong focus on input validation, object-oriented principles, and structured method usage.

The application was developed to meet the requirements of a multi-part assignment, consisting of:

✅ Part A: Program Class
Implements core utility methods:
InputValue(int min, int max) – Ensures a valid integer within a specified range
IsValid(string id) – Validates a book ID format: two uppercase letters followed by three digits (e.g., CS123)

✅ Part B: Book Class
Manages book data using:
Public static arrays of categoryCodes and categoryNames
Auto-implemented properties: BookTitle, NumOfPages, and Price
Full property validation for BookId and derived CategoryNameOfBook
Book ID assignment logic that defaults to "Miscellaneous (MI)" if category is unknown
Two constructors: a default constructor and one with full initialization
An overridden ToString() method for formatted book data output

✅ Part C: Application Logic
Extends the functionality using:
GetBookData(int num, Book[] books) – Gathers input from the user for each book, validates IDs and assigns categories
DisplayAllBooks(Book[] books) – Displays all entered books using each book's ToString() output
GetLists(int num, Book[] books) – Allows the user to input category codes and view all books in a specific category, along with a count
A complete Main() method that:
Gets number of books (between 1 and 30)
Calls GetBookData() to input books
Calls DisplayAllBooks() to show all books
Calls GetLists() to allow filtered viewing by category

💡 Key Features
✔️ Strong input validation (numeric range and string format)
✔️ Object-oriented design with encapsulation and constructors
✔️ Category recognition from book ID (e.g., CS123 → "Computer Science")
✔️ Fallback to "Miscellaneous" for unknown codes
✔️ Search/filter books by category
✔️ Reusable and modular method design

🛠 Technologies Used
C# (.NET Console Application)
.NET 6.0 / 7.0 / 8.0 compatible
Visual Studio IDE

