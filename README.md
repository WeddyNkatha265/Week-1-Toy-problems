# Week-1-Toy-problems

# Code Challenges: JavaScript Fundamentals snippets
# Challenge 1: Student Grade Generator

Write a function that prompts the user to input student marks. The input should be between 0 and 100. The output should correspond to the correct grade, as shown below:

A: > 79
B: 60 to 79
C: 59 to 49
D: 40 to 49
E: less than 40
Example usage:

JavaScript

const studentMarks = parseFloat(prompt("Enter student marks:"));
const grade = calculateGrade(studentMarks);
console.log(`Grade: ${grade}`);

# Challenge 2: Speed Detector
Write a program that takes the speed of a car as input (e.g., 80). If the speed is less than 70, it should print “Ok.” Otherwise, for every 5 km/h above the speed limit (70), it should give the driver one demerit point and print the total number of demerit points.

Example: If the speed is 80, it should print: “Points: 2.” If the driver gets more than 12 points, the function should print: “License suspended.”
Example usage:

JavaScript

const carSpeed = parseFloat(prompt("Enter car speed (km/h):"));
const demeritPoints = calculateDemeritPoints(carSpeed);
console.log(`Demerit Points: ${demeritPoints}`);

# Challenge 3: Net Salary Calculator
Write a program to calculate an individual’s net salary by getting the inputs of basic salary and benefits. Calculate the payee (tax), NHIF deductions, NSSF deductions, gross salary, and net salary.

Use actual KRA, NHIF, and NSSF values provided in the link below.
Example usage:

JavaScript

const basicSalary = parseFloat(prompt("Enter basic salary:"));
const benefits = parseFloat(prompt("Enter additional benefits:"));

// Calculate deductions and net salary
// ...

console.log(`Net Salary: KES ${netSalary.toFixed(2)}`);
