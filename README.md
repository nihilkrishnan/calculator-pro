# calculator-pro
# html
```c
<!DOCTYPE html>
<html lang = "en">
<head>
<title> JavaScript Calculator </title>

<style>
 h1 {
      text-align: center;
      padding: 23px;
      background-color: skyblue;
      color: white;
    }


#clear{
width: 270px;
border: 3px solid gray;
	border-radius: 3px;
	padding: 20px;
	background-color: rgb(119, 98, 211);
}

.formstyle
{
width: 350px;
height: 640px;
margin: auto;
border: 3px solid skyblue;
border-radius: 10px;
padding: 20px;
}



input
{
width: 20px;
background-color:rgb(123, 73, 210);
color: black;
border: 3px solid gray;
	border-radius: 10px;
	padding: 26px;
	margin: 5px;
	font-size: 15px;
}


#calc{
width: 250px;
border: 5px solid black;
	border-radius: 3px;
	padding: 20px;
	margin: auto;
}

</style>

</head>
<body>
<div class= "formstyle">
<form name = "form1">
	
  <input id = "calc" type ="text" name = "answer"> <br> <br>

  <input type = "button" value = "AC" onclick = "form1.answer.value += 'AC' ">
  <input type = "button" value = "DEL" onclick = "form1.answer.value += 'DEL' ">
  <input type = "button" value = "%" onclick = "form1.answer.value += '%' ">
  <input type = "button" value = "." onclick = "form1.answer.value += '.' ">
  <br> <br>

  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">
  <br> <br>
  
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">
  <br> <br>
  
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">
  <br> <br>
  
  
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">
    <input type = "button" value = "." onclick = "form1.answer.value += '.' ">

  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">
  <br> 
 
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >
  <br> 
  
</form>
</div>
</body>
</html>
```
# css 
```c
<style>
 h1 {
      text-align: center;
      padding: 23px;
      background-color: skyblue;
      color: white;
    }


#clear{
width: 270px;
border: 3px solid gray;
	border-radius: 3px;
	padding: 20px;
	background-color: rgb(91, 133, 218);
}

.formstyle
{
width: 300px;
height: 530px;
margin: auto;
border: 3px solid rgb(95, 74, 212);
border-radius: 5px;
padding: 20px;
}



input
{
width: 20px;
background-color: green;
color: white;
border: 3px solid gray;
	border-radius: 5px;
	padding: 26px;
	margin: 5px;
	font-size: 15px;
}


#calc{
width: 250px;
border: 5px solid black;
	border-radius: 3px;
	padding: 20px;
	margin: auto;
}

</style>
```
# output
![image](https://github.com/nihilkrishnan/calculator-pro/assets/118120621/1cccc0b8-8805-4e86-bff6-d29fd98a0c9c)
