Program Structure Solutions
===========================


1. Write a loop that makes seven calls to console.log to output the following triangle:

                        #
                        ##
                        ###
                        ####
                        #####
                        ######
                        #######
It may be useful to know that you can find the length of a string by writing .length after it.
   ```javascript
      for (let line = "#"; line.length < 8; line += "#")
      console.log(line);
      ```

2. Write a program that uses console.log to print all the numbers from 1 to 100, with two exceptions. For numbers divisible by 3, print "Fizz" instead of the number, and for numbers divisible by 5 (and not 3), print "Buzz" instead.

When you have that working, modify your program to print "FizzBuzz" for numbers that are divisible by both 3 and 5 (and still print "Fizz" or "Buzz" for numbers divisible by only one of those).

```javascript
for (let n = 1; n <= 100; n++) {
  let output = "";
  if (n % 3 == 0) output += "Fizz";
  if (n % 5 == 0) output += "Buzz";
  console.log(output || n);
}
```
