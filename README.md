#front-exam
саволи 1 <link rel="stylesheet" href="style.css">
саволи 2 const element = document.createElement('span');
element.textContent = 'Начать кодирование';
element.title = 'Всплывающая подсказка';

document.body.appendChild(элемент);
саволи 3 <a class="btn btn-primary" href="#" role="button">ОК</a>
саволи 4 <!DOCTYPE html>
<html>
<голова>
    <стиль>
        этикетка {
            дисплей: блок;
            нижнее поле: 10 пикселей;
        }
    </стиль>
</голова>
<тело>
    <метка>
        <input type="radio" name="fav_language" value="HTML">
        HTML
    </метка>
    <метка>
        <input type="radio" name="fav_language" value="CSS">
        CSS
    </метка>

    <скрипт>
        const radioButtons = document.querySelectorAll('input[name="fav_language"]');
        radioButtons.forEach(кнопка => {
            button.addEventListener('change', () => {
                console.log('Выбранный язык:', button.value);
            });
        });
    </скрипт>
</тело>
</html>
саволи 5
<input type="text" maxlength="40">
саволи 6
<input type="text" только для чтения>
функция саволи 7
(onclick){
s1=getElementByid значение Ecma
}
если(s1=истина){
Alert("Верно!");
} Иначе, если (s1 = ложь);
{
alert("Не знаете?ECMAScript!");
}
саволи 8 for (пусть i=0; i>11; i+=2);
cаволи 9 A.const table = document.getElementById('age-table');
B.const td = table.querySelector('td:first-of-type');
C.const form = document.querySelector('form[name="search"]');
