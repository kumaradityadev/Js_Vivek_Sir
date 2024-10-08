Statements vs Expressions 

let sum = 1+2;
let sum = Statements , 1+2; = Expressions ;

left hand side statements & right hand side Expressions 

Truthy/falsy Values 

There are only six falsy values in JavaScript:  Anything that is not falsy it truthy.
Falsy values in JavaScript:
1. False
2. 0
3. "" (empty string)
4. Null
5. Undefined
6. NaN (Not a Number)


Equality Operators
its sign 2 type 
1. == (Loose Equality) 2. === (Strict Equality)

1. == (Loose Equality)
Checks value equality only Ignores data type
ex : var x = 10;
var y = 10;
var z = ( x==y)
console.log(z);

2 === (Strict Equality)
Checks both value and data type equality
var x = 10;
var y = '10';
var z = ( x===y)
console.log(z);


Mathematical operators 
1. Addition (+)
2. Subtraction (-)
3. Multiplication (*)
4. Division (/)
5. Modulus (%)
6. Exponentiation ()

var a = 2
var b = 3
var c = a + b
var d = a * b
var e = a / b
var f = a - b

var a = 21;
var b = 2;
var  c = (a % b)
console.log(c);

// Exponentiation (**)
var a = 2;
var b = 3;
var c = a**b ;
console.log(c);

Relational operators 

Comparison Operators

1. Equal To (==)
2. Not Equal To (!=)
3. Strict Equal To (===)
4. Strict Not Equal To (!==)
5. Greater Than (>)
6. Less Than (<)
7. Greater Than or Equal To (>=)
8. Less Than or Equal To (<=)
20 > 10
10 > 20
10 > 10

Output:
true
false
false

Logical Operators
Logical OR (||)

its return always first truthy value .  

let a = false;
let b = 0;
let c = null;

let z = a || b || c;

console.log(z); output is null 

Logical AND (&&)
y pahle false search karta hai , yadi isko pahle false value mil gya to false return kare g nahi to last k true value return kare g . 

let a = 0;
let b = 'Vivek';
let c = 'Rishi';

let z = a && b && c;

console.log(z); output = 0


Automatic conversion type is called Type coercion


