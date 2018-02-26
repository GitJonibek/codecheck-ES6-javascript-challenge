# codecheck-ES6-javascript-challenge
Information
ECMAScript 6, also known as ECMAScript 2015, is the latest version of the ECMAScript standard. ES6 is a significant update to the language, and the first update to the language since ES5 was standardized in 2009. Implementation of these features in major JavaScript engines is underway now.
You can find more details in official document

This is a basic challenge to learn ES6 by implementing simple features!

Step1, Hello world
Fix hello.js to pass test

Step2, Class
Fix person.js to pass test

Step3, Inheritance
Polygon is a class which means a simple shape.
It can calculate its area size and has following subclasses

Rectangle
Square
Circle
Now Square and Circle class are not implemented yet.

Complete polygon.js to pass test

Specification
Square

Its constructor parameter is 1 number. It means a side length.
Circle

Its constructor parameter is 1 number. It means a radius.
The height of Circle is radius * 2.
The width of Circle is radius * 2.
Step4, Promise
Complete promise.js to pass test

Specification
sleep function returns Promise. Its value is specified time.
sleep function finish asynchronously after specified time.
if specified time is less than 0, the Promise rejected.
You can use setTimeout in sleep function.
Step5, Caesar cipher
Caesar cipher is a simple algorithm which makes encrypted text.

Complete cipher.js to pass test

Specification
Allowed characters are "abcdefghijklmnopqrstuvwxyz".
If not allowed character is present in input parameter, its character is not converted and included in result string.
Restriction
You MUST NOT use for statement.
If you are using for test fails.

Notes
Support uppercase in your implementation.
Each characters converted to same as lowercase.

Test Results before solving the challenge
codecheck: Finish with code 9
codecheck: tests  : 16
codecheck: success: 7
codecheck: failure: 9
Test Results after solving the challenge
codecheck: Finish with code 0
codecheck: tests  : 16
codecheck: success: 16
codecheck: failure: 0
Run Tests
To run tests locally install codecheck by running the following command in terminal.

$ npm install codecheck -g
To run tests in web editor please click in RUN button on left side of web editor.

