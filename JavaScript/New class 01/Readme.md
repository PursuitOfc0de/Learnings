## VARIABLES
Variables act as containers to store values.Variables are created using keywords(var, let and const) along with assignment operator(=) and a unique names (Identifier).

-- Some rules for making identifiers:-
Names can contain letters, digits, underscores, and dollar signs.
Names must begin with a letter.
Names can also begin with $ and _ (but we will not use it in this tutorial).
Names are case sensitive (y and Y are different variables).
Reserved words (like JavaScript keywords) cannot be used as names.

# Note :
- You can either declare a variable first and then initialize or, you can declare and intialize in a single line.
Ex:
var a;
a= 10;      or,  var a=10;
- You can declare multiple variables in a single line:
let person = "Ram", carName = "Honda", price = 200000 ;

# concatenated 
- Adding of strings or arrays to other strings or arrays or variable :

    - var a = 10+ "Ram" ;   will give output "10Ram"
    - var concat = "Ram" + "Shyam"; will give "RamShyam"

- Var : 
        it can be reintialized , but not redeclared.


- Let :
        it can be           , and can't be redeclared.


- Const :
        Always use const if the value should not be changed
        Always use const if the type should not be changed (Arrays and Objects)
