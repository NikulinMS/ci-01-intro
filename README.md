# Домашнее задание к занятию "`Жизненный цикл ПО`" - `Никулин Михаил Сергеевич`

## Основная часть

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

1. Open -> On reproduce.
2. On reproduce -> Open, Done reproduce.
3. Done reproduce -> On fix.
4. On fix -> On reproduce, Done fix.
5. Done fix -> On test.
6. On test -> On fix, Done.
7. Done -> Closed, Open.
![img_1.png](img%2Fimg_1.png)


Остальные задачи должны проходить по упрощённому workflow:

1. Open -> On develop.
2. On develop -> Open, Done develop.
3. Done develop -> On test.
4. On test -> On develop, Done.
5. Done -> Closed, Open.
![img_2.png](img%2Fimg_2.png)


**Что нужно сделать**

1. Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done. 
1. Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done. 
1. При проведении обеих задач по статусам используйте kanban. 

![img_3.png](img%2Fimg_3.png)
![img_4.png](img%2Fimg_4.png)
![img_5.png](img%2Fimg_5.png)

1. Верните задачи в статус Open.
1. Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.

![img_6.png](img%2Fimg_6.png)
![img_7.png](img%2Fimg_7.png)
![img_8.png](img%2Fimg_8.png)
![img_9.png](img%2Fimg_9.png)
![img_10.png](img%2Fimg_10.png)
![img_11.png](img%2Fimg_11.png)

Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания (скриншоты указаны выше, где описываются пути задач).

- [Bug.xml](src%2FBug.xml)
- [Other.xml](src%2FOther.xml)