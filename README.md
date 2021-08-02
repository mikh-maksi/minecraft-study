# Обучение Minecraft
Цель данного курса - чтобы в школах Харькова начали применять новые технологии обучения программированию для детей. Для этого планируется использовать среду Minecraft Education.
## Что такое Minecraft Education
**Minecraft Education** - это официальный мод одной из самых популярных игр в мире - Minecraft.  
От обычной версии игры она отличается тем, что в ней реализован блок программирования. Программировать можно ландшафт, действия и перемещения игрока и специально добавленного персонажа - агента.  
  
## Каков инструментарий Minecraft?
Это среда, в которой с помощью блоков можно создавать элементы аналогичные реальному миру: можно садить сады и лес, строить дома, бассейны, пирамиды, создавать дороги и делать на них разметку, строить железные дороги. А также создавать мобов и учитывать различные действия под большинство событий, которые происходят в мире.

## С чего начать?
Есть два навыка, которые необходимы в **Minecraft Education**: первый более сложный - это играть в **Minecraft**, второй - более простой и понятный после первого - это настраивать миры, загружать и сохранять код.

## Как играть в Minecraft?
Существуют различные режимы в Minecraft: приключение, выживание и творческий. В первых двух - вы развиваетесь - добываете ресурсы, строите из них дома, собираете себе еду. Научиться этому можно посмотрев ролики в Интернет. Научиться играть очень важно, потому что это нужно для формирования навыков работы с инструментами Minecraft.  
*Задание:* Построить дом из любого материала (можно это сделать из блоков дубовых досок или других материалов). 
После того, как сделали дом - продемонстрируйте его всем на занятии.

## Как программировать в Minecraft Education?
В данном моде есть 2 основных возможности для построения элементов: 
- Создание блоков в мире в соответствии с координатами
- Программирование агента.

## Алгоритмы структурного программирования в Minecraft:
### Событийно-ориентированное программирование.  
В **Minecraft Education** реализована парадигма событийно-ориентированного программирования. Т.е. действия выполняются при условии определенного события. Чаще всего используются события использования определенного предмета или же написание команды в чате.  
Реализуем управление передвижением агента через использование инструментов и через команды чата.

### Линейные алгоритмы.  
Самые простые линейные алгоритмы мы уже реализовали: передвигаем агента и/или игрока.  
В действиях, которые мы можем выполнять в Minecraft на уровне сложности, которая соответствует линейным алгоритмам: выполнение математических операций, в том числе остаток от деления; Перевод единиц измерения; В том числе - можно запрограммировать вычисление теоремы Пифагора и далее - проверить эти вычисления на практике.  
Также к линейным алгоритмам относится работа с переменными. В них можно сохранять координаты (например игрока) и вычислять относительно них перемещения агента, либо создание мобов.


### Линейные алгоритмы в пространстве.  
Для того, чтобы реализовать понимание линейных алгоритмов удобно создавать блоки по координатам. Например - поставить блок, а рядом с ним еще один. Или поставить блоки через каждые 4 блока.  
Также один из форматов перевода единиц измерения - это работа со временем (засечка моментов времени между событиями).
Один из удачных приемов объяснения координат - это относительные координаты (относительно игрока). Спросить - где будет размещен блок, если игрок находится в определенном положении.

### Генератор случайных чисел.  
В Minecraft можно запустить генератор случайных чисел. В том числе в формате создания блока в случайном положении.
*И добавить игровой элемент с баллами и временем?*

### Циклы  
Повторяемые действия - позволяют запускать в работу агента для выполнение ним повторяющихся действий, например, размещение блоков.
Комбинация циклических блоков, команд перемещения агента, а также команд установки блоков позволяют развивать навыки работы с циклами.  
**Например:**  
- посадить грядку цветов  
- посадить чередующиеся грядки цветов  
- построить лестницу  
- построить "греческий" орнамент  
- написать агентом букву  

### Циклы с параметром  
В этих алгоритмах - мы можем демонстрировать смену элементов благодаря тому, что меняется активная ячейка.

### Операторы выбора.  
Демонстрацию работы оператора выбора удобно проводить с установкой условий на выполнение задач в условиях, когда работает цикл с параметром.  

### Операторы выбора. Остаток от деления.  
**Остаток от деления** - это один из очень важных операторов в программировании. Один из наглядных примеров - это создание зубцов (на заборе или на башне) либо нанесение разметки на дороге.  
Также важным примером демонстрации остатка от деления и оператора выбора является постройка железной дороги, где через каждый 4 блока электрорельсов идет активатор.

### Массивы.  
В Minecraft Education - массивы позволяют задавать те действия (в том числе и последовательность активных ячеек, которые должен выполнить агент). Например - при создании фонаря.

### Двумерные массивы.  
В Minecraft Education - двумерные массивы можно применить, например, для замощения пространства "тратуарной" плиткой.

### Работа со строками.  
В Minecraft Education существует 

### Функции.
Первым знакомством с функциями (в том числе с параметрами) является обработка команд чата. Сами продемонстрировать работу с функциями как с блоками кода удобно на задании создания алфавита. А также продемонстрировав ребятам, что использование функций очень сильно экономит пространство для работы.

### Объектно-ориентированное программирование.  
С таким типом программирования мы работаем когда переходим на программирование на JavaScript. В этом случае объектом является тот, к кому применяется действие (игрок, агент), для объекта мы задаем действия (методы) и у объекта могут быть значения (поля).

## Темы по математике Minecraft: