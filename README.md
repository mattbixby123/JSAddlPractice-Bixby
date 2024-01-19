# JSAddlPractice-Bixby

Frontend Wev Dev with JavaScript - additional practice Pt. 1

link: https://docs.google.com/document/d/1ss_XPmTsZPmPm5cJ3jkW9DNfFrFhbvCmSnBlmWDbJ-M/edit#heading=h.6kvylad374c

Frontend Web Dev with JavaScript
Additional Practice
This document provides additional practice on the following objectives:
Write functioning Javascript inside an HTML file's head in a script tag
Identify some of the most common data types in Javascript: undefined, Number, String, and Function via their syntax
Identify some of the common data types in JS via the typeof operator (undefined, number, string)
Use console.log to show information about javascript
Recognize and write JavaScript number syntax (including negative numbers, decimals).
Recognize and write JavaScript string syntax (including quotes, double quotes, and template literals).
Use basic JavaScript number syntax and operations (addition, subtraction, multiplication, division, modulo).
Combine strings with string concatenation.
Predict the results of various operations on data types (type coercion)
Declare variables with let & const
Choose variable names that communicate the purpose of a variable to other developers.

Setup
Open up VSCode and create a new HTML file called index.html.
Create a basic boilerplate HTML file. Hint: VSCode comes with a shortcut, if you type “!” and hit tab, it should automatically set you up with some basic HTML.
In the <head> section of your file, create a <script></script> tag. This is where we will write our JavaScript code.
For now, just write a simple console.log statement in between the script tags.
If you have the Live Server extension installed on VSCode, right click on the HTML file, and click “Open With Live Server”. If not, find your index.html file in Finder on Mac, or File Explorer on Windows. Right click the file, and open with Google Chrome.
Once your browser is open, right click anywhere on the page, and click Inspect.
This should bring up the console, and you should see your console.log message there.

Temperature Converter:
Write a program to convert Fahrenheit to Celsius and Kelvin.
Suppose the temperature outside is 75°F. Create a variable called tempFahrenheit, and assign it the value 75.
The formula to convert Fahrenheit to Celsius is : Celsius = (Fahrenheit - 32) \* 5/9
Use this formula to calculate the temperature in Celsius, and store the result in a variable called tempCelsius, log it to the console.
Now that we have the temperature in Celsius, we can convert it to Kelvin by adding 273.15, store the result in a variable called tempKelvin, log it to the console.
Lastly, create a variable called todaysForecast, assign it a string value that says the following: “The current temperature outside is <temp in Fahrenheit> degrees Fahrenheit, <temp in celsius> degrees Celcius, and <temp in Kelvin> degrees Kelvin.” Print todaysForecast to the console.
Try changing the value of tempFahrenheit to something else, and run the program again. What happened to the other values?
What if you assign tempFahrenheit a string value, like “83”. How does that affect the output? Try it out, and log the data type of tempCelsius and tempKelvin.
Try assigning tempFahrenheit a negative value.

Bonus:
Use the Math.floor() method to round the results to a whole number.
Create reusable code by creating a function to perform the conversions:
The function should accept one parameter (the temperature in Fahrenheit) and return a string that says: “The current temperature outside is <temp in Fahrenheit> degrees Fahrenheit, <temp in celsius> degrees Celcius, and <temp in Kelvin> degrees Kelvin.”

Personalized Greeting:
Write a program that creates a personal greeting message:
Declare a variable, and assign it to your first name. Remember, this value won’t change, so keep that in mind when deciding which variable type to use.
Create another variable to store your last name.
Next, create a third variable to store your age.
Lastly, create a variable to store what city you’re from.
Using string interpolation, print the following message to the console: “Hello! My name is <first name> <last name>! I’m <age> years old, and I’m from <city>. It’s nice to meet you!
Try declaring a new variable to hold your initials. The value should be the first letter of your first name, and the first letter of your last name. Do this dynamically, so if the value of firstName or lastName changes, the initials will reflect the change automatically. Log your initials to the console.
Try entering a new name and run the program again. Did the initials change automatically?
Declare another variable called nameLength. The value should be the length of your first name. Again, avoid entering this manually, instead, see if you can assign the variable using the built in .length property.

    Bonus:

Try using some built in string methods to print your name in all caps, or all lower case.
Create reusable code by writing a sayGreeting function. The function should accept the following parameters:
firstName
lastName
age
city
and return a greeting “Hello! My name is <first name> <last name>.
I’m <age> years old, and I’m from <city>. It’s nice to meet you!
Try calling the function without passing in the city argument. What happens to your message?

Submission
To submit this assignment, put a GitHub link or screenshot of your work below and email this document to your instructional team members (ITMs). Make sure this document, and all links, are viewable by your ITMs.
