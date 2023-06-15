# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```


## OUTPUT
![Screenshot 2023-06-11 044216](https://github.com/Lillyjagan/Ex07_Web-Design/assets/128703180/f7dba808-174b-4585-9e86-d6f049972b72)
![Screenshot 2023-06-11 044255](https://github.com/Lillyjagan/Ex07_Web-Design/assets/128703180/e0bdf736-2e85-47d4-96c8-60af59259e3a)
![Screenshot 2023-06-11 044325](https://github.com/Lillyjagan/Ex07_Web-Design/assets/128703180/c26e575f-aafb-48bc-ad78-d2944b1ef7d6)
![Screenshot 2023-06-11 044353](https://github.com/Lillyjagan/Ex07_Web-Design/assets/128703180/49d847e2-e294-4cff-928c-18c2b8945636)
![Screenshot 2023-06-11 044427](https://github.com/Lillyjagan/Ex07_Web-Design/assets/128703180/38e90b9b-3c4d-4939-a210-033100cf7b4e)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
