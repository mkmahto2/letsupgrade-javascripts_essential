Question 1:

Take a number from a user and write a function which checks whether the number is even or
odd. Assign the result to a variable and log that variable in the console.
Example Input: 23
Output: The number entered is 23 and Number is odd
~~~
<!doctype html>
<html>
<head>
<script>
function odd_even(){
var no;
no=Number(document.getElementById("no_input").value);
if(no%2==0)
{
alert("Even Number");
document.write("Number is even "+no+"<br>")
}
else
{
alert("Odd Number");

document.write("Number is odd  "+num+"<br>")
}
</script>
</head>
<body>
Enter Any Number:<input id="no_input"><br />
<button onclick="odd_even()">Click me</button>
</body>
</html>
~~~
Question 2:


Write a program which will take OS name and version from the user separated by a space. Then
log the OS name and version on the console.
Input: "Android 9"
Output: The OS name is Android and version is 9

Question 3:

Write a program to take marks as input from the user and grade him accordingly. Use Conditional
statements. Also the same code using switch or ternary
input: 50
Output : Marks are 50 and grade is B
