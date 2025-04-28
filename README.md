C# Domain Testing Assignment
Overview
This project involves writing C# classes and methods for basic validation tasks and implementing domain testing through unit tests.
Create classes, write logic methods, and test them at critical boundary points.

Tasks
1. Voting Eligibility Checker
Class: Citizen

Method: IsEligibleToVote(int age)

Logic:
A citizen is eligible to vote if their age is between 18 and 120, inclusive.

Domain Test Cases:
Test with ages: 17, 18, 120, 121.

2. Password Validator
Class: User

Method: IsValidPassword(string password)

Logic:
A password is valid if its length is between 6 and 12 characters.

Domain Test Cases:
Test with password lengths: 5, 6, 12, 13.

3. Grade Validator
Class: GradeSystem

Method: IsValidGrade(int grade)

Logic:
A grade is valid if it falls between 0 and 100, inclusive.

Domain Test Cases:
Test with grades: -1, 0, 100, 101.

4. Discount Calculator
Class: Shop

Method: IsDiscountApplicable(decimal purchaseAmount)

Logic:
Discount is applicable if the purchase amount is between 50 and 500, inclusive.

Domain Test Cases:
Test with purchase amounts: 49.99, 50, 500, 500.01.

Testing Framework
using MS Test, .NET framework
Each test should focus on boundary value analysis and cover the specified domain values.
