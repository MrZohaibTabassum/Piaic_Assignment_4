// Assignment no: 1

// Name: Muhammad Zohaib Tabassum
// ID: PIAIC239431
// Center: UMT, Lahore


// Declare a variable named greeting with the string value "Hello, World!" and print it.
let greeting: string = "Hello, World!";
console.log(greeting);

// Define two variables with integer values and calculate their sum, difference, product, and quotient.
let num1: number = 10, num2: number = 20;
let sum: number, difference: number, product: number, quotient: number;
sum = num1 + num2;
difference = num1 - num2;
product = num1 * num2;
quotient = num1 / num2;
console.log("Sum: ", sum);
console.log("Difference:", difference);
console.log("Product: ", product);
console.log("Quotient: ", quotient);

// Swap the values of two variables without using a third variable.
let a = 1;
let b = 2;
a = a + b;
b = a - b;
a = a - b;
console.log("a:", a);
console.log("b:", b);

// This applies to TypeScript. Create a string variable and try changing its type.
let message: string;
message = "3";
console.log(message);

// Use the modulus operator to find the remainder of two numbers
let remainder: number = num1 % num2;
console.log("Remainder: ", remainder);

// Increment a variable's value by 1 using two different methods.
let counter: number = 1;
counter++;
console.log("Method 1: Incremented counter value:", counter)
counter = 1;
counter = counter + 1;
console.log("Method 1: Incremented counter value:", counter);

// Given three boolean variables, write expressions for AND, OR, and NOT gates.
let p: boolean = true;
let q: boolean = false;
let r: boolean = true;
let AND_result: boolean = p && q && r;
let OR_result: boolean = p || q || r;
let NOT_result: boolean = !a;
console.log("AND result", AND_result);
console.log("OR result", OR_result);
console.log("NOT result", NOT_result);

// Show examples of using compound assignment operators.
let num: number = 10;
num += 2;
console.log("After using +=:", num);
num -= 3;
console.log("After using -=:", num);
num *= 4;
console.log("After using *=:", num);
num /= 5;
console.log("After using /=:", num);

// Write a program to check if a number is even or odd.
let num4: number = 8;
if (num4 % 2 == 0) {
    console.log("Even");
}
else {
    console.log("ODD");
}

// Check if a person is eligible to vote.
let age: number = 23;
if (age >= 18) {
    console.log("you are eligible for voting");
}
else {
    console.log("You are not Eligible for voting");
}

// Assign a grade based on a numerical score.
let score: number = 85;
if (score >= 80 && score <= 100) {
    console.log("A Grade");
}
else if (score >= 60 && score <= 80) {
    console.log("B Grade");
}
else if (score >= 40 && score <= 60) {
    console.log("C Grade");
}
else if (score >= 20 && score <= 40) {
    console.log("D Grade");
}
else {
    console.log("F Grade");
}

// Find the maximum of three numbers.
let x: number = 4;
let y: number = 8;
let z: number = 9;
let max: number;
if (x >= y && x >= z) {
    max = x;
}
else if (y >= x && y >= z) {
    max = y;
}
else {
    max = z;
}
console.log("The Maximum of", x + ",", y + ",", z + " is", max);

// Check if a given year is a leap year.
let year: number = 2024;

if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
    console.log(year + " is a leap year.");
} else {
    console.log(year + " (is not a leap year.");
}

// Write a program that converts temperature from Fahrenheit to Celsius.
let fahrenheit: number = 98.6;
let Celsius: number = (fahrenheit - 32) * 5 / 9;
console.log("Fahrenheit to Celsius", Celsius);

// Check if a number is positive, negative, or zero.
let num5: number = -6;
if (num5 >= 0) {
    console.log(num5, " is Positive ");
}
else if (num5 == 0) {
    console.log(num5, " is Zero ");
}
else {
    console.log(num5, " is Negative ");
}

// Write a program that prints the multiplication table of a given number up to 10.
let num6: number = 5;
let prod: number;
for (let i = 1; i <= 10; i++) {
    prod = num6 * i;
    console.log(num6, " * ", i, "=", prod);
}
