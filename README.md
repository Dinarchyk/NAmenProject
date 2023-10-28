# NAmenProject

Сайт по прокату велосипедов 
Минимальная структура спринга на rest<br/>
1)Реализовать как минимум 3 сущности и реализовать связь с базой с помощью ORM
Пример:
- Сущность “Велосипед” у нее есть поля (id, author, characteristics, motherland)(произвести разметку сущностей
с помощью JPA)
- Сущность “Пользователь” у нее есть поля (id , fio, number, bicycleInShare)
- Сущность “Склад” у нее есть поля (id, address, bicycle, countIn, countOut)

2)Реализовать минимальный frontend сайт для отображения данных
Пример:
- Реализовать Сайт на котором пока вывожу велосипеды и список пользователей
- Реализовать DAO и Сервис для вывода данных по велосипедам и пользователям

3)Задание на функционал системы
- Реализовать Авторизацию и Регистрацию (Frontend & Backend)
- Прикрутить Spring security (Frontend & Backend)

4)Задание на функционал системы
- Реализовать Добавление велосипедов в базу (Frontend & Backend)
- Реализовать DAO и Сервис для добавления велосипедов в базу

5)Задание на функционал системы
- Реализовать Фильтр для поиска по разным параметрам велосипедов(Frontend & Backend)
- Реализовать DAO и Сервис для реализации различных Фильтров

6)Задание на функционал системы
- Реализовать Страницу пользователя в которой можно будет посмотреть все выданные ему велосипеды(Frontend & Backend)
- Реализовать DAO и Сервис для для вывода данных по пользователю, а именно данные по выданным ему велосипедам

7)Задание на функционал системы
- Реализовать Ролевую модель и учесть её в системе (имеется в виду Frontend & Backend)
- Реализовать роль “Администратора” которая дает пользователю доступ на просмотр данных по каждому пользователю
- Реализовать роль “Арендатор” дает доступ только к своей карточке и общей аренде велосипедов

8)Задание на читаемость своего кода
- Произвести Code Review своего кода
- Имеется переменная с наименованием a -> заменить на countPage
- Имеется дублирующий код -> необходимо оптимизировать и избавиться от дублирования на сколько это возможно
- Сделать так чтоб переменные, методы, классы и т.д имели корректный осмысленный вид
