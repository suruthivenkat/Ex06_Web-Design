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
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![Screenshot (25)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/6ad2f7ca-ba7c-43fc-b1d3-909f0e1a3e51)
![Screenshot (26)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/c4864b6f-bb99-4e21-8072-44e3091a78de)
![Screenshot (27)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/0e028b05-32e1-45ec-8533-2009fe85570c)
![Screenshot (28)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/20674579-3db3-48d6-9e5f-596b4ad0cfb3)
![Screenshot (29)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/a4df5885-73f5-45d2-b0de-f73e379008e7)
![Screenshot (30)](https://github.com/suruthivenkat/Ex06_Web-Design/assets/168054678/4a87c42d-e13f-47e4-87dc-8632fbfb9e45)




## RESULT
  Student result using JavaScript is created successfully.
