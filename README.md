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
