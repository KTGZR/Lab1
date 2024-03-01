<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Белов Ярослав Евгеньевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №1.«Введение в веб-разработку»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Веб-разработка</b> — процесс создания веб-сайта или веб-приложения. Основными этапами процесса являются веб-дизайн, вёрстка страниц, программирование на стороне клиента и сервера, а также конфигурирование веб-сервера.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Требуется создать простой сайт с информацией о себе и своём хобби.</p>

<p>ГРАФИЧЕСКИЕ ТРЕБОВАНИЯ 1:</p>
<ul>
<li>Информация о себе</li>
<li>Информация о хобби</li>
<li>Фотография</li>
</ul>



<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовался:</p>

<ul>
<li>Материалом в сети интернет</li>
</ul>

<h2 align = "center">Файл Index.html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Me</title>
    <link rel="icon" type="image/x-icon" href="orel.ico">
    <link rel="stylesheet" href="stylemain.css">
    
</head>
<body bgcolor="#99ffff">
    <h1 style="font-size: 120px;position: relative;bottom: 100px;">Это моя история</h1>
    
    <img src="wave.gif" alt="GIF" height="100px" width="100%" style="position: relative;bottom: 200px;">
    <div style="position: relative;bottom: 90px;">
    <img src="я.jpg" alt="Моё фото" height="450px" class="right scrug" style="position: relative;bottom: 50px;">
    <p style="position: relative;bottom:125px;font-size: 20px;" >Я Белов Ярослав,мне 19 лет, я студент направления Прикладаная математика и иформатика Сахалинского государственного
     университета.
    Я прошел 3 семестра и еще раз понял, что выбрал нужное и интересное мне направление. За время учебы я успел побывать в
     студсовете и поработать на благо университета.
     Говоря о моих хобби, я бы хотел привести в пример готовку. Я пытаюсь совершенствоваться в этом дeле. Я могу проводить много времени за этим даже не замечая времени. Больше всего я люблю готовить супы.<br>
     Вот пример простого <a href="https://www.russianfood.com/recipes/recipe.php?rid=141964" target="_blank" style="position: relative;right: 25px;">куриного супа.</a><br>
     <img src="суп.jpg" hspace="5"><br>
     Также немного о моих достижениях:
     <hr style="position: relative;bottom: 100px;">
     <ul style="position: relative;bottom: 100px;">
        <li>Прошел курсы будь готов</li>
        <li>Участвовал в нескольких олимпиадах по информатике</li>
        <li>Участвовал в организации мероприятий для студентов</li>
     </ul>
     <hr style="position: relative;bottom: 100px;">
     
    </p>
</div>
 
    
</body>
</html>
```

<h2 align = "center">Файл Index.html</h2>

```htmlmixed
.right
{float:right;
    margin: 0 0 5px 5px;
}
.scrug
{   border-radius: 10px;
    border: 5px #23cc5c solid;
    box-shadow: 0 0 10px #444;
}
a:link,a:visited{color: red;background-color: transparent;text-decoration: none;padding: 15px 25px;text-align: center; display: inline-block;}
a:hover,a:active{color:yellow; background-color: transparent;text-decoration: none;}
```


<h1 align = "center">Результат</h1>

<p align = "center"><img src="Резласт.png" alt="Screenshot"></p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я познакомился с языком разметки HTML, а также познакомился с языком разметки Markdown.</p>
