# String Review
+ Review user stories of Sprint on 22 August 2025

  OK
# The 2nd Sprint Task:
## User Story 1:
Key Points Covered:

PHP Tags: PHP code is enclosed within tags, and = ?> for short echo syntax.

Variables: Variables in PHP begin with the $ symbol, followed by the variable name.

Statements & Semicolons: PHP statements end with semicolons (;), signaling the end of an instruction.

Data Types: PHP supports a variety of data types, including strings, integers, booleans, arrays, and objects.

Control Structures: If-else, loops (for, while, foreach), and switch statements were also discussed.

Functions: Functions are defined using the function keyword followed by a name and parentheses for parameters.

<?php
$say = "hello";

Example:

<?php

namespace App\Http\Controllers;

 use Illuminate\Http\Request;

class testController extends Controller
{
    public function index(){

        $Duong = "Hello world";
        echo $Duong;
    return view('testView');
    }
    
}
Review Outcome: The user story was successfully completed. All the key elements of PHP syntax were clearly understood, including variables, operators, loops, and control structures. php Syntax.
# Test Environment.
## User Story 2:

php programming Control The goal of this user story was to explore how PHP manages program flow, including loops, conditional statements, and function control.

Key Points Covered:

If Statements: Used to execute code based on conditions.

Switch Case: A control structure that allows multi-way branching.

Loops: Loops like for, while, and foreach were explored to execute repetitive tasks.

Break & Continue: These keywords allow control over the flow of loops, with break exiting the loop and continue skipping to the next iteration.

Function Calls: Functions were discussed as a method for breaking up code into reusable pieces, with the return statement used to output values.

Review Outcome: The task was completed successfully. All concepts related to control structures in PHP were covered effectively, and understanding of how to manage control flow in PHP was demonstrated.

<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = $_POST["name"];
    echo "Xin chào, " . htmlspecialchars($name) . "!";
}
?>

<form method="post">
    Nhập tên của bạn: <input type="text" name="name">
    <input type="submit" value="Gửi">
</form>

## User Story 3:
Methods This user story focused on understanding PHP methods, which are essential for structuring and organizing code, particularly in object-oriented programming.

Key Points Covered:

Defining Methods: Methods are functions defined inside classes in PHP and are used to define behaviors for objects.

Public, Private, and Protected Methods: PHP supports different access modifiers for methods, allowing for the restriction or exposure of functionality.

Static Methods: Methods that belong to the class itself, rather than to instances of the class.

Constructor and Destructor: Special methods for initializing and cleaning up objects (__construct, __destruct).

_ Calling Methods: Methods are invoked using the object or the class name, depending on whether they are instance or static methods.

Review Outcome: This user story was completed successfully. The concept of methods, including access modifiers and static methods, was well understood.

## User Story 4:
Php in Web App Development This user story emphasized the role of PHP in the broader context of web application development.

Key Points Covered:

Dynamic Content Generation: PHP is widely used to generate dynamic web pages by embedding PHP code within HTML.

Database Interaction: PHP works seamlessly with MySQL (or other databases) for CRUD operations (Create, Read, Update, Delete).

Sessions and Cookies: PHP handles user sessions and cookies, which are essential for maintaining state across page requests.

Handling Forms: PHP is used to process form data sent via GET or POST methods, including validation and saving to a database.

Security: PHP includes built-in functions for security, like filtering input, protecting against SQL injection, and using prepared statements.

Frameworks: Tools like Laravel make PHP development even more efficient by offering features like routing, middleware, and ORM (Eloquent).

Review Outcome: This user story was successfully completed. PHP's role in web development was clearly understood, including its ability to create dynamic pages, interact with databases, and manage sessions.
