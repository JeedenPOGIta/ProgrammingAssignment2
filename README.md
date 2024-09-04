# [Problem 1 - Normalization problem] <br><br>

<h3>Description and thought process</h3><br>

The normalization problem asks the program to "normalize" the given random array. This can be done <br>
by simply getting the mean of the array and "centralizing the values by subtracting the mean to <br>
each value, and dividing the centralized values by the standard deviation. <br><br> 

To create this program, we first need to import the Numpy functions as such: <br>

![image](https://github.com/user-attachments/assets/537bccca-36a0-4bfd-ba44-c59633a295fc) <br>

Then, we create a 5x5 array and fill it with random integers. We can achieve this by using the <br>
"np.random.random()" function. However, this function will fill the array with float values <br>
but in our case, we need integers. Hence, we tweak the function a bit. By using the "randint()" <br>
function. The syntax is as follows: <br>

![image](https://github.com/user-attachments/assets/f8fe497f-38a5-48e8-a668-8892a65831f6) <br>

After we create the 5x5 array, we now must perform different mathematical functions to get <br>
the necessary values to plug in the formula of normalization. Let us first start with gettingv<br>
the mean of the array by using the ".mean()" function. Once obtained, we subtract the mean to <br>
each of the individual 'x' elements of the array. After, we get the standard deviation of the <br>
array by using the ".std()" function, and finally, we plug in the values in the formula of <br>
normalization. The line of code is as follows: <br>

![image](https://github.com/user-attachments/assets/750b177c-eaac-4f81-9ff7-f378e952d6ab) <br>

The formula for normalization: <br>
![image](https://github.com/user-attachments/assets/d0b33d15-05f3-476a-a18a-a6440fe7fcf2) <br>

And, of course, we output the normalized values of the array. <br><br>

# [Problem 2 - Divisible by 3 Problem] <br><br>
<h3>Description and thought process</h3><br>

The Divisible_by_3_problem is a program that displays the squares of the first 100 positive integers <br>
that is placed in a 10x10 array and identifies which of the values are divisible by 3. <br>

To create the program, just like the first problem, we need to import Numpy as np. After, we need to <br>
create a 10x10 array containing the squares of the first 100 positive integers. This can be achieved <br>
by using the ".arange()" function together with the ".reshape()" and exponentiation " ** " functions. <br>
The syntax is as follows: <br>

![image](https://github.com/user-attachments/assets/3e2fad47-91ee-4592-8934-b8dabdad0ccc) <br>

Now that you have the array setup, it is time to create the divisibility checker using a for loop. <br>
This is so that we can check each individual element of the array and print them if they satisfy <br>
the condition of being divisible by 3. This can be achieved by using a for loop with the modulo  <br>
and equal functions. The syntax will be as follows: <br>

![image](https://github.com/user-attachments/assets/d104a3a1-e728-4725-9cc0-2cb68b65dd17) <br>

If you instead put "print(array[i,j])" at the end of the loop, you might find yourself presented <br>
with a list of values listed in a vertical manner. This might be fine for some people but not in <br>
my case. Hence, I found a way to list them horizontally using an output variable and ".append()" <br>
function together with the ".join()" and "map()" function to turn the list into single string and <br>
display the outputs in a neat and clean manner. <br><br>

# [END OF THE REPOSITORY] <br>

And that is a wrap! This is the end of my repository on our programming assignment 2. Please let me <br>
know if you have any feedback, tips, tricks, or suggestions for improving my coding efficiency! <br>
Thank you once again!



