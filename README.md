<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CALCULATOR BY ME</title>
   <style>
       #cal {
    height: 360px;
    width: 250px;
    border: 1px solid rgb(114, 104, 104);
    border-radius: 5px;
    background-color: rgb(11, 29, 109);

}

#display {
    width: 90%;
    height: 10%;
    display:flex ;
    justify-content: center;
    margin: 10px;
border: 1px solid rgb(128, 122, 122);
border-radius: 5px;
background-color: rgba(0, 0, 0, 0.699);
color: rgb(13, 172, 172);
}

.button_container {
     display: flex;
     justify-content: center;
     flex-wrap: wrap;
     margin: 5px;
     background-color: rgb(6, 46, 99);
}



.button {
  width: 50px;
  height: 50px;
  margin: 5px; 
  background-color: rgb(14, 114, 145);
}
</style>


</head>
<body>

  
    <div id="cal"> 

   <input type="text" id="display" readonly>


   <div class="button_container">
   <button class="button" onclick="currentDisplay+='1'
    document.querySelector('#display').value=currentDisplay;">1</button>

   <button class="button" onclick="currentDisplay+='2'
    document.querySelector('#display').value=currentDisplay;">2</button>

   <button class="button"  onclick="currentDisplay+='3'
    document.querySelector('#display').value=currentDisplay;">3</button>

   <button class="button"  onclick="currentDisplay+='+'
    document.querySelector('#display').value=currentDisplay;">+</button>

   <button class="button"  onclick="currentDisplay+='4'
    document.querySelector('#display').value=currentDisplay;">4</button>

   <button class="button"  onclick="currentDisplay+='5'
    document.querySelector('#display').value=currentDisplay;">5</button>

   <button class="button"  onclick="currentDisplay+='6'
    document.querySelector('#display').value=currentDisplay;">6</button>

   <button class="button"  onclick="currentDisplay+='-'
    document.querySelector('#display').value=currentDisplay;">-</button>

   <button class="button"  onclick="currentDisplay+='7'
    document.querySelector('#display').value=currentDisplay;">7</button>

   <button class="button"  onclick="currentDisplay+='8'
    document.querySelector('#display').value=currentDisplay;">8</button>

   <button class="button"  onclick="currentDisplay+='9'
    document.querySelector('#display').value=currentDisplay;">9</button>

   <button class="button"  onclick="currentDisplay+='*'
    document.querySelector('#display').value=currentDisplay;">*</button>

   <button class="button"  onclick="currentDisplay+='0'
    document.querySelector('#display').value=currentDisplay;">0</button>

   <button class="button"  onclick="currentDisplay+='/'
    document.querySelector('#display').value=currentDisplay;">/</button>

   <button class="button"  onclick="currentDisplay+='.'
    document.querySelector('#display').value=currentDisplay;">.</button>

   <button class="button"  onclick="
   let result= eval(currentDisplay);
   currentDisplay= result;
    document.querySelector('#display').value=currentDisplay;">=</button>

   <button class="button"  onclick="currentDisplay=''
    document.querySelector('#display').value=currentDisplay;">C</button>
</div>
   

<script> 
    let currentDisplay = '';
    document.querySelector('#display').value=currentDisplay;

</script>
</body>
</html>
