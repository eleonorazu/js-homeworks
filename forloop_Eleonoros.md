# Tasks

1. Using a for loop, print even numbers from 2 to 20.
!!Solution!!

function printEvenNumbers() {
  for (let i = 0; i <= 20; i += 2) 
  console. log(i); } 
printEvenNumbers()

2. Using a while loop, print odd numbers from 1 to 15.

!!Solution!!
let number = 1;
while (number <= 15) {
  console.log(number);
  number += 2;
}


3. Using a for loop, print the numbers from 1 to 100, but only if they are divisible by 7.
for (let i = 1; i <= 100; i++) {
  if (i % 7 === 0) {
    console.log(i);
  }
}

4. Using a for loop, find the sum of numbers from 1 to 100, but exclude numbers divisible by both 3 and 5.

!!Solution!!
for (let i = 1; i <= 100; i++) {
  if (i % 15 === 0) {
    console.log(i);
  }
}


or 


function divisibleBy3and5() { 
    for (let i = 1; i <= 100; i++) { 
        if (i % 3 == 0 && i % 5 == 0) { 
            console.log(i) 
        } 
    } 
} 
 divisibleBy3and5() 

5. Using a for loop, print a pattern of stars in reverse:

```
*****
****
***
**
*
```

6. Using a for loop, print a pattern of numbers in a pyramid shape:

```
   1
  123
 12345

```

7. Using a for loop, calculate the factorial of 10.

!!Solution!!
let factorial = 1;

for (let i = 1; i <= 10; i++) {
  factorial *= i;
}

console.log(factorial);
8. Using a while loop, print the numbers from 10 to 1 in reverse order.

!!!Solution!!
let number = 10;
while (number >=1) {
  console.log(number);
  number -= 1;
}

9. Using a do-while loop, print the numbers from 5 to 1 in reverse order.
!!SOLUTION!!
let i = 5;
const n = 1;

do {
    console.log(i);
    i--;
} while(i >= n);

10. Using a for loop, print a pattern of alternating letters and numbers:
```
A1
B2
C3
D4
E5

```
!!Solution!!
for (let i = 1; i <= 5; i++) {
  // Get the corresponding letter based on ASCII code
  let letter = String.fromCharCode('A'.charCodeAt(0) + i - 1);

  // Print the alternating pattern of letters and numbers
  console.log(letter + i);
}
11. Using a for loop, print the numbers from 50 to 1, but only if they are divisible by 5.
for (let i=50; i>=1;i--){
  if(i%5===0){
    console.log(i)}
}
12. Using a for loop, print numbers from 1 to 100, but replace multiples of 3 with "Three" and multiples of 7 with "Seven".
for (let i=1; i<=100;i++){
  if(i%3===0){
    console.log("three")}
  else if(i%7===0){
    console.log("seven")
  }
  else console.log(i)
}
13. Using a for loop, print a pattern of stars:

```
    *
   ***
  *****
 *******
*********

```
!!Solution!!
function createPyramid(number) {
  for(let i = 1; i <= number; i++) {
    let row = '';
    
    for (let j = 1; j <= number - i; j++) {
      row += ' ';
    }
  
    for (let k = 1; k <= 2 * i - 1; k++) {
         row += '*'
    }
    console.log(row)
  }
}
 
const pyramidHeight = 5;
 
createPyramid(pyramidHeight)

14. Using a for loop, print a pattern of numbers:

```
12345
 1234
  123
   12
    10
```
15. Using a for loop, print a pattern of letters:

```
ABCDE
 ABCD
  ABC
   AB
    A

```
16. Using a for loop, calculate the sum of the first 10 cube numbers.
!!Solution!!
let sum = 0;

for (let i = 1; i <= 10; i++) {
  let cube = i * i * i;
  sum += cube;
}
console.log(sum);

17. Using a while loop, print numbers from 1 to 15, but skip numbers that are multiples of 3.
!!SOLUTION!!
let i=1; 
while (i<=15){
  if(i%3!=0){
  console.log(i)
  }
  i++
}

18. Using a do-while loop, print the first 10 natural numbers.
!!SOLUTION!!
let i = 1;
const n = 10;
do {
    console.log(i);
    i++;
} while(i <= n);

19. Using a for loop, find the product of numbers from 1 to 10, but exclude 7.
!!SOLUTION!!
for (let i=1;i<=10;i++){
  if  (i!=7){
    console.log(i)
  }
}

20. Using a for loop, print numbers from 1 to 25, but replace multiples of 4 with "four".
    for (let i=1;i<=25;i++){
  if  (i%4===0){
    console.log("four")
  }
  else console.log(i)
}

22. Using a for loop, print numbers from 1 to 100, but replace multiples of 3 with "Fizz" and multiples of 5 with "Buzz". If a number is both a multiple of 3 and 5, print "FizzBuzz".
!!Solution!!

for (let i=1;i<=100;i++){
 if (i%3===0&&i%5===0){
   console.log(i+"FizzBuzz")
 } 
 else if (i%3===0){
   console.log(i+"Fizz")
 }
  else if(i%5===0){
    console.log(i+"Buzz")
  }
}

22. Using a for loop, find and print the sum of all prime numbers between 1 and 50.
let sum = 0;

for(i = 1; i <= 50; i++){
  
  sum += i;
}
console.log(`sum of first ${i-1} natural numbers is: `, sum);

23. Using a for loop, print the first 10 numbers in the Fibonacci sequence, but start with 0 and 24. Using a for loop, find the product of the first 10 positive even numbers.

25. Using nested for loops, print a pattern of stars in a diamond shape:

