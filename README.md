Javascript outbased Question



1. Increment Operator (a++)

let a = 1;
let b = a++;
console.log(a, b);
Output:
2 1

Why?
a++ is post-increment
It first assigns the value, then increments





2. AND Operator (&&)
console.log(0 && "Hello");
console.log("Hello" && 0);

Output:

0
0


3. OR Operator (||)

console.log(0 || "JS");
console.log("" || "Default");

👉 Output:


JS
Default


✅ Rule:
|| returns the first truthy value

👉 So:

0 is falsy → "JS" is returned
"" is falsy → "Default" is returned

4.
console.log('2' - 1);
👉 Output: 1
Why?

In JavaScript, the - (minus) operator forces type conversion (called type coercion).

'2' is a string
1 is a number
When using -, JavaScript converts '2' → 2 (number)


5.console.log(2 + true);

👉 Output: 3

Why?

In JavaScript, true is treated as 1 when used in numeric operations.






