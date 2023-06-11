# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
<title>JavaScript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"));
mark2=parseInt(prompt("Enter Subject-2 Marks"));
mark3=parseInt(prompt("Enter Subject-3 Marks"));
total=mark1+mark2+mark3;
percentage=total/3;
if((percentage>=91)&&(percentage>=100))
{
  alert("O Grade");
}
else if((percentage>=81)&&(percentage>=90))
{
  alert("A+ Grade");
}
else if((percentage>=71)&&(percentage>=80))
{
  alert("A Grade");
}
else if((percentage>=61)&&(percentage>=70))
{
  alert("B+ Grade");
}
else if((percentage>=51)&&(percentage>=60))
{
  alert("B Grade");
}
else
{
  alert("RA Grade");
}

}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
## OUTPUT
![WhatsApp Image 2023-06-03 at 7 22 28 PM](https://github.com/Shalini-Rajan/Ex06_Web-Design/assets/128398163/92b15c0a-6827-4d40-9c43-0c5abe789d43)


## RESULT
  Student result using JavaScript is created successfully.
