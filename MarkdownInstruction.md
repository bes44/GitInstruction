# Изменение разметки при помощи Markdown

# Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).
✦ = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого
(“=”) и второго (“-”) уровней.
✦ ** Полужирное начертание** или __ Полужирное начертание__
✦ *Курсивное начертание* или _Курсивное начертание_
✦ ***Полужирное курсивное начертание***
✦ ~~Зачёркнутый текст~~
✦ * Строка – ненумерованные списки, символ “*” в начале строки
✦ 1, 2, 3 … – нумерованные списки
```C#
while(n<10>)
{
    n--;
}
```
```python
if x > 0:
	print (x)
else:
	print ('Hello, World!')
```

```c
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

```javascript
let x = 12;
let y = 6;
console.log(x + y);
```

Для переноса строки внутри одного параграфа есть три метода:

поставить в конце строки два или больше пробела   ;
поставить в конце строки обратную косую черту \;
использовать HTML-тег <br>.

##Таблицы 

|Столбец 1|Столбец 2|Столбец 3|
|:-|:-:|-:|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|
|Запись|Запись|Запись|

##Экранирование (escaping characters)
обратная косая черта \. 
нужно экранировать: \`*_{}[]<>()#+-.! |

Как использовать Markdown в мессенджерах
Как мы уже писали, принципы Markdown используются при разметке текста во многих мессенджерах. Обычно он используется для выделения текста, при этом синтаксис у каждой платформы свой.

Жирный:

Telegram и Discord — **две звёздочки с двух сторон**;
WhatsApp и Viber — *одна звёздочка с двух сторон*.
Курсив:

Telegram — __два нижних подчёркивания с двух сторон__;
WhatsApp и Viber — _одно нижнее подчёркивание с двух сторон_;
Discord — *одна звёздочка с двух сторон* или _одно нижнее подчёркивание с двух сторон_.
Подчёркнутый:

Discord — __два нижних подчёркивания с двух сторон__.
Зачёркнутый:

WhatsApp и Viber — ~одна тильда с двух сторон~;
Discord — ~~две тильды с двух сторон~~.
Моноширинный (используется для вставки кода):

Telegram, WhatsApp, Viber и Discord — ```три обратных апострофа с двух сторон```;
в Discord точно так же, как и в Markdown, можно указывать язык программирования для подсветки синтаксиса.
Спойлер:

Telegram и Discord — ||две вертикальные черты с двух сторон||.