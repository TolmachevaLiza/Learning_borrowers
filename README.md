# Исследование надёжности заёмщиков
Описание проекта Заказчик — кредитный отдел банка. 
-------------------------------------------------
В данном проекте на основе статистики о платёжеспособности клиентов, провели исследование как влияет семейное положение и количество детей клиента на погашения кредита в срок.
Цель данного проекта ответить на следующие вопросы:
1) На какие нужды клиенты берут кредит?
Чаще всего клиенты берут кредит на недвижимость, автомобиль, образование и свадьбу. Самой популярной целью кредита - кредит на недвижимость.
2) Есть ли зависимость между наличием детей у клиента и погашения кредита в срок? 
Создадим таблицу, где выведем какой процент людей имеет задолжность по каждой группе.
| Два ребенка | Многодетная семья | Нет детей | Один ребенок 
--------------|-------------------|-----------|--------------
  9.454191    |    8.552632       | 7.544358  |  9.234609   
Из таблицы сделали вывод, что многодетные семьи имеют меньше долгов, чем те у кого нет детей. Наличие детей у клиента влияет на погашение кредита в срок.
3) Есть ли зависимость между семейным положением и возвратом кредита в срок?
Сгруппировав данные вывели в процентном соотношении зависимость задолжности от Семейного положения.
∣ Не женат / не замужем ∣ Женат / замужем ∣ вдовец / вдова |
∣-----------------------∣-----------------∣----------------|
∣  9.750890             ∣    7.545182     ∣    6.569343    |
Как можно заметить, что вдовец / вдова имееют меньше долгов, чем не женатые и не замужние. 
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

Два ребенка | Многодетная семья  | Нет детей | Один ребенок | Один ребенок  
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |---
9.454191 | 8.552632 | 7.544358 | 9.234609 
