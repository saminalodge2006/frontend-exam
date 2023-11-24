саволи 1 <link rel="stylesheet" href="style.css">
саволи 2 const element = document.createElement('span');
element.textContent = 'StartCoding';
element.title = 'Всплывающая подсказка';

document.body.appendChild(element);
саволи 3 <a class="btn btn-primary" href="#" role="button">Ok</a>
саволи 4 <!DOCTYPE html>
<html>
<head>
    <style>
        label {
            display: block;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <label>
        <input type="radio" name="fav_language" value="HTML">
        HTML
    </label>
    <label>
        <input type="radio" name="fav_language" value="CSS">
        CSS
    </label>

    <script>
        const radioButtons = document.querySelectorAll('input[name="fav_language"]');
        radioButtons.forEach(button => {
            button.addEventListener('change', () => {
                console.log('Selected language:', button.value);
            });
        });
    </script>
</body>
</html>
саволи 5 <input type="text" maxlength="40">
саволи 6 <input type="text" readonly>
саволи 7 function(onclick){
s1=getElementByid Ecma value
}
if(s1=true){
Alert("Верно!");
}else if(s1=false);
{
alert("Не знаете?ECMAScript!");
}
саволи 8 for (let i=0; i>11; i+=2);
cаволи 9 A.const table = document.getElementById('age-table');
B.const td = table.querySelector('td:first-of-type');
C.const form = document.querySelector('form[name="search"]');