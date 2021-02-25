<p align = center>МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ

<p align = center>РОССИЙСКОЙ ФЕДЕРАЦИИ

<p align = center>ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ

<p align = center>«ВЯТСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»

<p align = center>Институт математики и информационных систем

<p align = center>Факультет автоматики и вычислительной техники

<p align = center>Кафедра систем автоматизации управления


<p align = right>Дата сдачи на проверку:

<p align = right>«___» __________ 2021 г.

<p align = right>Проверено:

<p align = right>«___» __________ 2021 г.

<p align = center>Методы формирования html5 документов

<p align = center>Отчет по лабораторной работе № 1

<p align = center>по дисциплине

<p align = center>«Основы frontend-разработки и организации человеко-машинного интерфейса»

<p align = center>Вариант 4




<p align = center>Разработал студент гр. ИТб-1301-01-00 ________________ /Голованов О.А./

<p align = center>Проверил ст. преподаватель _________________ /Земцов М.А./

<p align = center>Работа защищена с оценкой	«___________» «___» __________ 2021 г.





<p align = center>Киров 2021

__________
Цель: изучение методов формирования html5 документов на стороне клиента.

Задачи:

1. Организовать рабочее пространство и процессы разработки html5 документов.
1. Изучить структуру html5 документа
1. Исследовать функциональные возможности инструментов разработчика на стороне браузера
1. Изучить типовые элементы структуры html5 документа
1. Составить отчет по выполненным задачам

Ход выполнения:

1. Организовать рабочее пространство и процессы разработки html5 документов.

В ходе лабораторной работы был установлен текстовый редактор IDE Visual Studio Code, который может быть расширен и адаптирован к языку программирования через использование плагинов. Также был установлен ряд плагинов:

- VSCode All Autocomplete
- Auto Close Tag
- Auto Complete Tag
- Auto Rename Tag
- Path Intellisense
- Prettier Formatter for Visual Studio Code vscode-multiclip
- Live Server
- Kite Autocomplete Plugin for Visual Studio Code
- GitLens — Git supercharged
- Font Awesome Auto-complete & Preview
- VS Code ESLint extension
- Code Runner
- Bootstrap 4, Font awesome 4, Font Awesome 5 Free & Pro snippets for Visual studio code
- Better Comments
- Visual Studio Code CSS Intellisense for HTML
- Visual Studio Code HTML Snippets



Также была проведена регистрация на сайте github.com и изучена документация по работе с git.

<p align = center>2

____________
В соответствии с заданием был создан репозиторий на сайте github.com с названием “Basic frontend dev labs”. В нем была создана ветка lab1, а также директория “bfdLabs”. Директория подключена к созданному репозиторию на github.com.

Ссылка на данный репозиторий представлена ниже.

*[Ссылка на репозиторий](https://github.com/OlegNeBot/Basic-frontend-dev-labs)*

2. Изучить структуру html5 документа

Была изучена документация по стандарту html4 и html5.

Задание 1: *Создайте HTML-страницу index4.html, разделенную на фреймы в соответствии с номером варианта. В качестве заголовка страницы используйте ваше имя, отчество и фамилию. Фреймы должны содержать:* 

*№1 – номер зачетной книжки;* 

*№2 – таблицу (варианты приведены на рис.3);* 

*№3 – ваше имя, отчество и фамилию;* 

*№4 – список дисциплин и преподавателей текущего семестра.*

Задание по 4 варианту представлено на рисунках 1 и 2.

<p align=center><img src=./lab1./pictures/Z1v4.png></p>

<p align = center>Рисунок 1 - задание на реализацию web-страницы с фреймом

<p align=center><img src=./lab1./pictures/Z1t4.png></p>

<p align = center>Рисунок 2 - задание для фрейма таблицы

В соответствии с номером варианта была реализована html-страница , представляющая разделение окна браузера на фреймы. Ссылка на фреймы - <https://github.com/OlegNeBot/Basic-frontend-dev-labs/tree/main/bfdLabs> . На рисунке 3 представлена html-страница index4.html, открытая в браузере.

<p align = center>3

_________
<p align=center><img src=./lab1./pictures/Z1index4.png></p>

<p align = center>Рисунок 3 - реализация страницы на html-4


Была проведена валидация результатов с помощью <https://validator.w3.org/#validate_by_input>. 

Ошибок в html страницах допущено не было.

Листинг страницы inde4.html представлен в приложении А.

Задание 2: *Создайте файл index.html, используя html5 разметку. Файл должен реализовывать предыдущее задание с использованием языка html5. Готовым решением будет успешное прохождение проверки валидации.*

Файл index.html был успешно создан и практически так же реализует предыдущее задание. Была также проведена валидация, в ходе которой ошибок найдено не было.

На рисунке 5 представлена HTML-страница index.html открытая в браузере. Листинг страницы index.html представлен в приложении Б.

<p align=center><img src=./lab1./pictures/Z2index.png></p>

<p align = center>Рисунок 4 – web-страница index.html

<p align = center>5

__________________________

Выводы по эволюции стандарта html5 и принципам преобразования (конвертации) документов из стандарта html 4 в версию 5: 

В html5 большая часть используемого контента в html4 была удалена. Разделение элементов на блочные и строчные используется в html до версии 4.01. В html5 эти понятия заменены более сложным набором контента, по которому каждый HTML-элемент должен знать какой контент для него допустим. Главным отличием html4 от html5 является то, что html5 больше работает с css, а html4 больше работает со своим содержимым. 


3. Исследовать функциональные возможности инструментов разработчика на стороне браузера

В рамках лабораторной работы был рассмотрен браузер Google Chrome на основе движка рендеринга chromium. Изучена документация по работе с devtools, а конкретно описание и ключевые возможности следующих панелей:

- панель Elements
- панель Console
- панель Sources
- панель Network
- панель Performance

<p align = center>6

__________________________
- панель Memory и JavaScript Profiler
- панель Application
- панель Security
- панель Audits

4. Изучить типовые элементы структуры html5 документа

В ходе выполнения работы были изучены типовые элементы структуры html5 документа.

Задание 3: *Прочитайте про теги разметки текста. Описание тегов приведено по ссылке: <https://html5book.ru/html-text/>.*

*По результатам ответьте на следующие вопросы:*

- Какие из тегов являются тегами форматирования абзацев?
- В чем различие тегов h?
- Для чего применяется тег code как его использовать?
- В чем различие тегов code, kbd, samp, var, pre?
- В чем отличие тегов оформления цитат и определений от тегов обычного форматирования текста?
- Для чего применяются теги p, br и hr?
- Какая разница в тегах span и p?
- В чем разница между тегами b и strong?

Ответы:

- Теги форматирования абзаца - p, br, hr.
- Теги h идут от самого большого к самому маленькому, то есть h1 намного выше, чем h6.
- Тег code предназначен для отображения строк программного кода. Его синтаксис выглядит так: <\code>текст<\/code> .
- Тег kbd выделяет текст, вводимый пользователем. Тег samp используется для вывода результата выполнения программного кода или скрипта, системных сообщений. Тег var выделяет переменные из программ и отображает их курсивом. Тег pre выводит текст без форматирования, сохраняя пробелы и переносы текста.
- Теги оформления цитат и определений используются для выделения неких аббревиатур, цитат(длинных и коротких), а также источника цитат.

<p align = center>7

__________________________________
- Эти теги применяются для разделения текста: тег p определяет текстовый абзац, тег br используется для переноса текста на новую строку, а тег hr создает горизонтальную линию для разделения параграфов.
- В отличие от тега p, тег span выделяет часть информации внутри других тегов и позволяет установить для нее свой стиль.
- Тег b, в отличие от тега strong, не придает тексту важности.

Задание 4: *Используя методы разметки текста реализуйте текущее расписание занятий на 2 недели. При реализации необходимо чтобы ссылки на онлайн лекции были меньше и выделены жирным курсивом, фамилия преподавателя была курсивом, а название дисциплины было h4. Использованием стилей недопустимо.*

Задание 4 доступно для просмотра по ссылке <https://github.com/OlegNeBot/Basic-frontend-dev-labs/tree/main/bfdLabs/raspisanie> 

5. Составить отчет по выполненным задачам

Отчет был успешно составлен после изучения документации по разметке markdown. Список используемой литературы представлен в приложении В.



Вывод: в ходе работы была изучены базовая структура html документов, а также были получены навыки в их формировании. Были исследованы возможности инструментов разработчика в браузере, а также язык разметки markdown.









<p align = center>8

_________
<p align = center>Приложение А

<p align = center>(обязательное) 

<p align = center>Листинг html-страницы index4.html

    <!DOCTYPE  HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
    <html>
    <head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Голованов Олег Алексеевич</title>
    </head>
     <frameset rows = "10%, 18%, 72%">
    <frame src = "i4zachet.html" name = "first">
    <frame src = "i4tabl.html" name = "second">
    <frameset cols = "45%, 55%">
    <frame src = "i4disprep.html" name = "third">
    <frame src = "i4fio.html" name = "fourth">
    </frameset>
    <noframes>
     Sorry, there is not a frame support in your browser.
    </noframes> 
     </frameset>
    </html>














<p align = center>9

__________
<p align = center>Приложение Б

<p align = center>(обязательное) 

<p align = center>Листинг html-страницы index.html

    <!DOCTYPE html> <!-- Объявление формата документа -->
    <html lang="ru">
    <head>
    <meta charset="UTF-8">
    <title>Голованов Олег Алексеевич</title>
    <style>
    #header{
    text-align:center;
    width:1250px;
    height:50px;
    }
    #menu{
    text-align:center;
    width:1250px;
    height:100px;
    }
    #footer{
    text-align:center;
    width:550px;
    height:400px;
    float :left;
    }
    #news{
    text-align:center;
    width:697px;
    height:400px;
    float: right;
    }
    </style>
    </head>
    <body>
    <div id="header"><IFRAME SRC = "i4zachet.html" width="1247" height="50" NAME="boot"></IFRAME></div>
    <div id="menu"><IFRAME SRC = "i4tabl.html" width="1247" height="100" NAME="boot"></IFRAME></div>
    <div id="footer"><IFRAME SRC = "i4disprep.html" height="450" width="550" NAME="boot"></IFRAME></div>
    <div id="news"><IFRAME SRC = "i4fio.html" width="697" height="450" NAME="boot"></IFRAME></div>
    </body>
    </html>














<p align = center>10

______
<p align = center>Приложение В

<p align = center>(справочное)

<p align = center>Библиографический список

- <https://githowto.com/ru> 
- <https://git-scm.com/book/ru/v2> 
- <http://htmlbook.ru/samhtml/vvedenie-v-html> 
- <https://html5book.ru/html-html5/> 
- <https://habr.com/ru/company/simbirsoft/blog/337116/> 
- <https://gist.github.com/Jekins/2bf2d0638163f1294637> 
- <https://www.vyatsu.ru/uploads/file/1604/101_2004.pdf>

<p align = center>11