## Домашна работа 1

#### Краен срок - 02.04.2015 23:56, Четвътрък
#### Краен срок на бонус задачата - 05.04.2015 23:55
#### Домашните се пращат на мейл: kn42014@gmail.com

### Задача 1
Реализирайте следните структури:
* точка (`point`), която да има координати х и у (`float`);
* отсечка (`segment`), която да има начало и край, които са от тип `point`;
* начупена линия (`polygonalLine`), която да има член-данна масив от отсечки и член-данна брой на отсечките в масива.

Реализирайте функция `polygonalLine longestPolygonalLine(polygonalLine* , int)`, която по зададен масив от начупени линии връща тази, с най-голяма дължина.

## Бонус задача
Дефинирайте си функция `sortLines`, която да сортира масив от начупени линии, и функция `int indexOfPolygonalLineBinarySearch`, която да приема сортирания масив и дължина на линия и да връща като резултат индекса на линията с тази дължина по [метода на двоичното търсене](http://en.wikipedia.org/wiki/Binary_search_algorithm), ако има такава линия, ако няма да върне -1.

### Задача 2
Реализирайте клас `AlcoholicDrink`

* Един вид алкохол има следните атрибути
  * `name` - име на типа напитка
  * `price` - цена на литър в лева
  * `abv` - (alcohol by volume) процент на алкохол в напитката

* и следните методи
  * `конструктор` - с три параметъра
  * `конструктор` - без параметри
  *  подходящи `set` и `get` методи за всички атрибути
  * `double waterToLowerPercentage(double wantedPercentage, double litersOfAlcohol)` - функция, която връща количеството вода в литри, нужни, за да се разреди напитката до съдържание на процент алкохол `wantedPercentage`, като `litersOfAlcohol` e количеството алкохол, което разреждаме

Дефинирайте и следните външни функции
* `AlcoholicDrink iWannaGetDrunk(AlcoholicDrink*, int)` - приема масив от напитки и връща тази, с най-високо съдържание на алкохол
* `AlcoholicDrink iWannaGetDrunkAndIAmAPoorFMIStudent(AlcoholicDrink*, int)` - приема масив от напитки и връща тази, чието отношение `%алкохол/цена` е най-високо

## Относно предаването:
Всяка задача трябва да е в отделна папка с име `task#`, в която да са само `task#.cpp` и `task#.h`, където # е номера на задачата (не целите проекти, ако използвате Visual Studio). (Бонуса се предава като част от задача 1) Изпратете един архив. В мейла не забравяйте да напишете име, факултетен номер и група. Както миналия семестър, така и сега ще проверяваме задачите автоматизирано, затова програмите ви не трябва да извеждат нищо. Успех!
