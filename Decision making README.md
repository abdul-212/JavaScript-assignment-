////=====================>>> JavaScript Decision-Making Exercises <<<===========================================///

///Exercise 1: Check if a Number is Positive, Negative, or Zero
//Write a JavaScript program that takes a number as input and checks whether it is positive, negative, or zero.

let num = prompt("Check the number is positive, negative or zero?");
if (num > 0) {
    console.log(num, "number is positive.");
} else if (num < 0) {
    console.log(num, "number is negative.");
} else {
    console.log(num, "number is zero.");
}

/// ==============================================>>>>>>=======================================///

/// Exercise 2: Check Even or Odd
/// Write a JavaScript program that takes a number and checks if it is even or odd.

let value = prompt("Check the number is even or odd?");
if (num / 2) {
    console.log("The value is even");
} else {
    console.log("The value is odd");
}
console.log(value);

/// ==============================================>>>>>>=======================================///

/// Exercise 3: Check Voting Eligibility
/// Write a JavaScript program that asks for a user's age and determines if they are eligible to vote (age should 
//  be 18 or above).

let age = prompt("Check if the age is eligible to vote.");
if (age >= 18){
    console.log("You are eligible to vote.");
} else {
    console.log("You are not eligible to vote.");
}
console.log(age);

/// ==============================================>>>>>>=======================================///

/// Exercise 4: Find the Largest of Two Numbers
/// Write a JavaScript program to find the largest of two numbers given by the user.

let num1 = prompt("You should check two numbers to see which is the largest number So, Enter the number 1");
let num2 = prompt("Enter your number 2");
if (num1 > num2){
    console.log("The largest number is num1",);
} else {
    console.log("The largest number is num2",);  
}
console.log("num1", num1, "; num2", num2);

/// ==============================================>>>>>>=======================================///

/// Exercise 5: Check If a Person is Eligible for a Discount
// A store gives a discount if:
// => The person is either a senior citizen (age 60 or above) or
// => The person has a membership card.
/// Write a JavaScript program that checks if a person is eligible for a discount.

let Age = prompt("If your age 60 or above so, Eligible for a Discount, Please Enter your Age");
let hasmembership = prompt("Or Do you have a membership card? (yes/no)")
if (Age >= 60 || hasmembership === "yes"){
    console.log("You are eligible for a discount.");
} else {
    console.log("You are not eligible for a discount.");
}

//
/// ==============================================>>>>>>=======================================///

// Exercise 6: Login System with Username and Password
// Write a JavaScript program that checks if the username is "admin" and the password is "12345". If both match, display "Login successful", otherwise "Invalid credentials".

let username = prompt("Login System with Username and Password, Please Enter username");
let password = prompt("Or Enter password");
if (username === "admin" && password === 12345){
    console.log("Login successful");
} else {
    console.log("Invalid credentials");
}

/// ==============================================>>>>>>=======================================///

// Exercise 7: Grade System
// Write a JavaScript program that takes a student's marks and assigns a grade based on the following criteria:
// (90 and above → A)  (80 to 89 → B)  (70 to 79 → C)  (60 to 69 → D)  (Below 60 → F)

let marks = prompt("Enter Your Percentage");
if (marks >= 90 && marks <= 100){
    console.log("Grade A");
} else if (marks >= 80 && marks <= 89){
    console.log("Grade B");
} else if (marks >= 70 && marks <= 79){
    console.log("Grade C");
} else if (marks >= 60 && marks <= 69){
    console.log("Grade D");
}else if (marks < 60){
    console.log("Grade F");
}
console.log("According to your marks, Your marks was:", marks);

/// ==============================================>>>>>>=======================================///

// Exercise 8: Traffic Light System
// Write a JavaScript program that takes a traffic light color as input ("red", "yellow", or "green") and prints the appropriate action:
// ("red" → "Stop");    ("yellow" → "Slow down");   ("green" → "Go");

let color = prompt("Enter the traffic light colors (Red, Yellow or Green):");
if (color === "Red") {
    console.log("Stop");
} else if (color === "Yello") {
    console.log("Slow down");
} else if (color === "Green") {
    console.log("Go");
} else {
    console.log("Invalid color! Please enter red, yellow, or green.");
}
console.log(color, "Signal");
