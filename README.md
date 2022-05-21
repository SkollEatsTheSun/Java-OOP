# Java-OOP
Lab work on studying the basics of object-oriented programming in Java.

Создать абстрактный класс «Бытовая техника» с методами: 
* public abstract void init(Scanner scanner) 	// считывание параметров с консоли
* public abstract String getCost()	// возвращает  стоимость
* public String toString() 		// возвращается состояние объекта в виде строки // (определяется только в наследниках, т.к. определен в 				// Object) 


Построить иерархию классов: 
- Бытовая техника
    - Газовая плита.
    - Электронная техника
        - Микроврллновка
        - Стиральная машина

Написать программу, которая: 
1. Считывает с консоли количество техники (распознавать количество техники при вводе пользователем таких строк: вап4явап, аа4а555 (в этом случае надо распознать первое число)) 
2. В цикле считывает параметры. Сначала спрашивается тип техники и создается объект нужного класса. Затем у объекта вызывается метод init() и вводятся характеристики объекта. Понятно, что метод init() разный у разных классов. 
3. Считанные объекты добавляются в массив 
4. Ищется бытовая техника с наибольшей стоимостью и выводится на экран (вывод через toString())

