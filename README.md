## Программно-вычислительный комплекс для вычисления температурных изменений в системе металл - жидкость.

=====

#### Все с чего-то начинают путь в программировании. Этот репозитой остается здесь, чтобы видеть, как поменялся мой стиль и уровень кода сквозь годы.


## 1.	ОПИСАНИЕ ПРИЛОЖЕНИЯ

Приложение создано для наглядного отображения изменения разницы температур при охлаждении металла жидкостью. Данный процесс описывается уравнением теплового баланса.

## 2.	РЕАЛИЗАЦИЯ ПРИЛОЖЕНИЯ

Приложение создано на основе объектно-ориентированного языка программирования Java (language level 6). Среда разработки -  IntelliJ IDEA 14 Community Edition. Вычисление основано на численных методах Эйлера и Рунге-Кутта.

## 3.	РАБОТА ПРИЛОЖЕНИЯ
Данное приложение отображает 3 графика зависимости  разности температур от времени с начала процесса охлаждения. Есть возможность изменения масштаба графиков и авто масштабирования.  Для графиков соответствующих методам Эйлера и Рунге-Кутта выводятся по 3 таблицы значений разности температур и времени, каждая из которых соответствует определенному шагу. Приложение позволяет сохранять все графики с текущим масштабом с различными параметрами в форматах *.png  и *.svg. Табличные данные можно сохранить в *.csv формате. Возможны комбинированные варианты сохранения данных (графики + таблицы) в форматах *.xls, *.pdf. В процессе работы с программой пользователь может ввести интересующую его разность температур и получить время, через которое она будет достигнута (для каждого из методов и каждого шага)
   
## 4.	ПАРАМЕТРЫ ПРИЛОЖЕНИЯ

При работе с данными, пользователь может задавать и редактировать следующие параметры:
1)	Начальные условия физической задачи (разность температур в нулевой момент времени);
2)	Коэффициент k для различных жидкостей
3)	Параметры графика (отображаемый отрезок, цвет графика, ориентация графика, фоновый рисунок, рамка, заголовки, шрифты). 


