# GE-IHW
### Документация  
#### Автор  
Баранов Егор  
#### Генерация  
Каждая комната состоит из нижнего и верхнего уровня, задача игрока поднятся из нижнего в верхний по платформам которые генерируются по правилам:  
- На уровне присутствуют несколько точек генерации, они расположены так, чтобы игрок обязательно мог добраться до верхнего уровня.  
- В каждой точке генерации случайно вызывается одна из заранее подготовленный платформ, по которым игрок должен взбираться до верхнего уровня.  
- На каждой платформе так же есть несколько точек спавна ловушек и/или баффов.  
- В начале каждой комнаты есть точка спавна случайного баффа.
- В данной реализации каждая новая комната это лишь изменение одного и того же уровня
#### Сложность  
- Изменение сложности происходит за счет увеличения урона статических и подвижных ловушек.
- За прохождение в легкие ворота сложность увеличивается на 1 условный пункт, за прохождение в сложные на 2 пункта
