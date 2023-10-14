# Nursery_with_animals

<div id="header" align="center">
  <img src="https://media.giphy.com/media/tXL4FHPSnVJ0A/giphy.gif" width="300"/>
</div>

# ubuntu

:blush: Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).



:blush: Создать директорию, переместить файл туда.

:blush: Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.

:blush: Установить и удалить deb-пакет с помощью dpkg.

:blush: Выложить историю команд в терминале ubuntu
<div id="header" align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZWozbDA0dG0zMWduN3NibnBqeXh2YXhqajRvNnU5c3B1NXZ0cWc3dyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/3o7TKHVU0xsgGDCyPu/giphy.gif" width="400"/>
</div>


---

# sql

:blush: Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).
![sXema](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/441f803a-38b5-4afb-bc0d-9294be87b99b)

:blush: В подключенном MySQL репозитории создать базу данных “Друзья
человека”

CREATE DATABASE Human_friends;

:blush: Создать таблицы с иерархией из диаграммы в БД
![sql](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/f0991624-5341-4fc3-8492-bf3e660655d3)

:blush: Заполнить низкоуровневые таблицы именами(животных), командами
которые они выполняют и датами рождения
![sql2](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/5c724978-5826-40bd-9577-3594ad105fbc)

:blush: Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой
питомник на зимовку. Объединить таблицы лошади, и ослы в одну таблицу.
![sql3](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/0aad0748-8923-4876-acbf-aee22c1574b2)

:blush: Создать новую таблицу “молодые животные” в которую попадут все
животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью
до месяца подсчитать возраст животных в новой таблице
![sql4](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/564fbefa-9972-443b-83cc-33e654fc24a5)

:blush: Объединить все таблицы в одну, при этом сохраняя поля, указывающие на
прошлую принадлежность к старым таблицам.
![sql5](https://github.com/TusyaSam/Nursery_with_animals/assets/114438495/975a6adb-7c11-4423-9044-676103dc164e)

---

# java

:disappointed_relieved: Создать класс с Инкапсуляцией методов и наследованием по диаграмме.

:disappointed_relieved: Написать программу, имитирующую работу реестра домашних животных.
В программе должен быть реализован следующий функционал:

:broccoli: Завести новое животное

:broccoli: определять животное в правильный класс

:broccoli: увидеть список команд, которое выполняет животное

:broccoli: обучить животное новым командам

:broccoli: Реализовать навигацию по меню


:disappointed_relieved: Создайте класс Счетчик, у которого есть метод add(), увеличивающий̆
значение внутренней̆  int переменной̆ на 1 при нажатие “Завести новое
животное” Сделайте так, чтобы с объектом такого типа можно было работать в
блоке try-with-resources. Нужно бросить исключение, если работа с объектом
типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение
считать в ресурсе try, если при заведения животного заполнены все поля.

<div id="header" align="center">
  <img src="https://media.giphy.com/media/gfsQffBnuc6e096brx/giphy.gif" width="400"/>
</div>
