![](https://miro.medium.com/v2/resize:fit:1200/1*tifNDBJM5QhgjZSTQYJR-Q.png)

1. charAt()
Метод возвращает символ, находящийся в указанной позиции строки.

Синтаксис:
str.charAt(index)

index — индекс символа в строке (нумерация с 0).
Возвращает символ строки на указанной позиции.

Пример:

let str = "Hello";
console.log(str.charAt(1));

2. at()
Метод возвращает символ на заданной позиции, включая поддержку отрицательных индексов (для доступа к символам с конца строки).

Синтаксис:

str.at(index)

index — индекс символа. Может быть отрицательным.
Возвращает символ на указанной позиции.

Пример:

let str = "Hello";
console.log(str.at(1)); 
console.log(str.at(-1));

3. toString()
Метод возвращает строковое представление объекта. Этот метод доступен для всех объектов в JavaScript.

Синтаксис:

obj.toString()

Возвращает строку, представляющую объект.

Пример:

let num = 123;
console.log(num.toString()); 

4. concat()
Метод объединяет два или более строковых значения и возвращает новую строку.

Синтаксис:

str1.concat(str2, str3, ...)


Возвращает новую строку, которая является объединением всех переданных строк.

Пример:

let str1 = "Hello";
let str2 = " world!";
console.log(str1.concat(str2)); 

5. trim()
Метод удаляет пробелы с начала и конца строки.

Синтаксис:

str.trim()

Возвращает новую строку без начальных и конечных пробелов.

Пример:

let str = "  Hello  ";
console.log(str.trim());

6. includes()
Метод проверяет, содержит ли строка подстроку.

Синтаксис:

str.includes(searchString, position)

searchString — строка, которую нужно найти.
position — (необязательный) индекс, с которого начинать поиск (по умолчанию 0).

Пример:

let str = "Hello world";
console.log(str.includes("world")); 
console.log(str.includes("hello")); 


7. indexOf()
Метод возвращает индекс первого вхождения подстроки в строке, или -1, если подстрока не найдена.

Синтаксис:

str.indexOf(searchValue, fromIndex)

searchValue — строка, которую ищем.
fromIndex — (необязательный) индекс, с которого начинается поиск (по умолчанию 0).

Пример:

let str = "Hello world";
console.log(str.indexOf("world"));
console.log(str.indexOf("abc")); 


8. replace()

Метод заменяет первое вхождение подстроки на новую строку.

Синтаксис:

str.replace(searchValue, newValue)

searchValue — строка или регулярное выражение для поиска.
newValue — строка для замены.

Пример:

let str = "Hello world";
console.log(str.replace("world", "JavaScript")); 


9. substring()

Метод извлекает подстроку между двумя индексами.

Синтаксис:

str.substring(startIndex, endIndex)

startIndex — индекс начала извлечения.
endIndex — (необязательный) индекс конца извлечения (не включая его).

Пример:

let str = "Hello world";
console.log(str.substring(0, 5));

10. slice()

Метод извлекает подстроку из строки, аналогичен substring, но поддерживает отрицательные индексы.

Синтаксис:

str.slice(beginIndex, endIndex)

beginIndex — индекс начала извлечения.
endIndex — (необязательный) индекс конца извлечения (не включая его).

Пример:

let str = "Hello world";
console.log(str.slice(0, 5));
console.log(str.slice(-5));

11. toLowerCase()

Метод возвращает строку в нижнем регистре.

Синтаксис:

str.toLowerCase()

Возвращает строку в нижнем регистре.

let str = "Hello World";
console.log(str.toLowerCase());

12. toUpperCase()

Метод возвращает строку в верхнем регистре.

Синтаксис:

str.toUpperCase()

Возвращает строку в верхнем регистре.

Пример:

let str = "Hello World";
console.log(str.toUpperCase());

13. split()

Метод разбивает строку на массив подстрок, разделенных указанным разделителем.

Синтаксис:

str.split(separator, limit)

separator — строка или регулярное выражение, по которому происходит разделение.
limit — (необязательный) максимальное количество элементов в возвращаемом массиве.

Пример:

let str = "apple,banana,cherry";
let arr = str.split(",");
console.log(arr); 

![](https://cdn.educba.com/academy/wp-content/uploads/2020/06/JavaScript-Number.jpg)
Вот информация о различных математических методах в JavaScript:

1. Math.floor(x)

Метод округляет число x вниз до ближайшего целого. То есть, он убирает дробную часть числа, не зависимо от ее значения.

Пример:

Math.floor(4.7);
Math.floor(-4.7); 

2. Math.ceil(x)

Метод округляет число x вверх до ближайшего целого. То есть, он всегда округляет число в большую сторону.

Пример:

Math.ceil(4.2); 
Math.ceil(-4.2); 

3. Math.round(x)

Метод округляет число x до ближайшего целого. Если дробная часть числа меньше 0.5, округляется в меньшую сторону, если больше или равна 0.5 — в большую сторону.

Пример:

Math.round(4.5); 
Math.round(4.4); 
Math.round(-4.5); 
Math.round(-4.6);

4. Math.abs(x)

Метод возвращает абсолютное (модуль) значение числа x. То есть, преобразует отрицательные числа в положительные.

Пример:

Math.abs(5);
Math.abs(-5);
Math.abs(0);


5. Math.max(...values)

Метод принимает одно или несколько значений и возвращает наибольшее из них.

Пример:

Math.max(1, 2, 3); 
Math.max(-1, -2, -3);
Math.max(5, 100, 2); 

6. Math.min(...values)

Метод принимает одно или несколько значений и возвращает наименьшее из них.

Пример:

Math.min(1, 2, 3); 
Math.min(-1, -2, -3);
Math.min(5, 100, 2); 


7. Math.pow(base, exponent)

Метод возводит число base в степень exponent. Это аналог оператора возведения в степень **.

Пример:

Math.pow(2, 3); 
Math.pow(4, 0.5);
Math.pow(5, -1); 

8. Math.sqrt(x)

Метод возвращает квадратный корень числа x. Если число отрицательное, возвращает NaN.

Пример:

Math.sqrt(9); 
Math.sqrt(16); 
Math.sqrt(2); 
Math.sqrt(-4); 



9. Math.random()

Метод возвращает случайное число в диапазоне от 0 (включительно) до 1 (не включая 1). Этот метод полезен для генерации случайных чисел.

Пример:

Math.random();
Math.random();

10. isNaN(value)

Метод проверяет, является ли переданное значение не числом (NaN). Возвращает true, если значение не является числом, и false, если значение числовое.

Пример:

isNaN(123); 
isNaN('123');
isNaN('abc');
isNaN(NaN); 
