

# Exercises: JavaScript loops

Paste your answers into this file.

<br>

## Print every number from 0 to 10

```
let n = 0;
for ( let i = 0; i < 11; i++){
	console.log(i)

}
```

<br>

## Print every number from 10 to 0

```
let n = 0;

for ( let i = 10; i > 0; i--){
	console.log(i)

}
```

<br>

## Print every number from 4 to -16

```
let n = 0;

for ( let i = 4; i > -15; i--){
	console.log(i)

}
```

<br>

## Print every fifth number from 8 to 41

```
let n = 8;

while (n < 42){
console.log(nn);
nn += 5;
}

8
13
 18
 23
 28
 33
 38
43
```

<br>

## The classic Fizzbuzz Program

For every `number` between 1 and 100...

If the `number` is evenly divisible by 3, print "Fizz"

If the `number` is evenly divisible by 5, print "Buzz"

If the `number` is evenly divisible by 3 AND evenly divisible by 5, print "Fizzbuzz"


```
for ( let i = 3; i < 100; i++){
	if (i % 3 === 0) {
      console.log("Fizz");
      
    }
     if (i % 5 === 0) {
      console.log("Buzz");
    }
if (i % 5 === 0 && i % 3 === 0) {
      console.log("FizzBuzz");
    }
        
      
console.log(i);
}
```

<br>


## The even/odd reporter

Write a for loop that will iterate from 0 to 20. For each iteration, it will check if the current number is even or odd, and report that to the screen (e.g. "2 is even").

```
for ( let i = 0; i < 21; i++){
	
	if( i % 2 === 0){
	console.log(`${i} is even`);
}

	if (i % 2 !== 0){
	console.log(`${i} is odd`);
}

}
```

<br>

## Multiplication Tables

Write a for loop that will iterate from 0 to 10. For each iteration of the for loop, it will multiply the number by 9 and log the result (e.g. "2 * 9 = 18").

Bonus: Use a nested for loop to show the tables for every multiplier from 1 to 10 (100 results total).


```
for ( let i = 0; i < 11; i++){
	let sum = i * 9	

console.log(`${i} * 9 = ${sum}`)
};
```

<br>

## The Grade Assigner

Check the results for every value from 60 to 100 - so your log should show "For 89, you got a B. For 90, you got an A.", etc.

```
for ( let i = 60; i < 101; i++){

	if ( i > 59 && i < 70){

		console.log(`For ${i}, you got a D.`); 
}

	if ( i > 69 && i < 80){

		console.log(`For ${i}, you got a C.`); 
}

if ( i > 79 && i < 90){

		console.log(`For ${i}, you got a B.`); 
}
if ( i > 89 && i < 101){

		console.log(`For ${i}, you got a A.`); 
}

}
```
