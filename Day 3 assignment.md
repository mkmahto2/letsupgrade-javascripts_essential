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
~~~
<!DOCTYPE html>
<html>
<head>
<title>Untitled document</title>
<meta charset="utf-8" />
<script language="javascript" type="text/javascript">
function calculategpa()
{
var marks = document.getElementById("txtmarks").value;
var gpa = document.getElementById("txtgpa");
if(marks >= 50 && marks <= 60)
{
gpa.value = "E";
}
else if(marks >= 61 && marks <= 70)
{
gpa.value = "D";
}
else if(marks >= 71 && marks <= 80)
{
gpa.value = "C";
}
else if(marks >=81 && marks<=90)
{
gpa.value = "B";
}
else if(marks >=91)
{
gpa.value = "A";
}

}
</script>
</head>
<body>
<form action="" method="post" name="frm">
<table width="471" height="257" border="1">
<tr>
<td>Enter Marks</td>
<td><input type="text" name="txtmarks" id="txtmarks"></td>
</tr>
<tr>
<td>GPA</td>
<td><input type="text" name="txtgpa" id="txtgpa"></td>
</tr>
<tr>
<td> </td>
<td><input type="button" name="btn1" id="btn1" value="Calculate" onClick="calculategpa();"></td>
</tr>
</table>
</form>
</body>
</html>
~~~
