# Упражнения

## Поднятие

1. Напишите функцию, содержащую внутри себя переменную с поднятием.
2. Опубликуйте пример с функцией на github.
3. Используйте eslint, для поиска проблем в коде и флаг --fix для их исправления.
4. При необходимости исправьте пример и отправьте изменеия на github.

## Скалярные и Ссылочные типы данных

Подготовьте две реализации функции `inc`:
1. C сигнатурой `inc(n: number): number`,
пример вызова: `let a = 5; const b = inc(a); console.dir({ a, b });`
2. C сигнатурой `inc(num: Num)`, где `Num` является объектом с полем `n`,
чтобы функция изменила поле исходного объекта переданного по ссылке,
пример вызова `let obj = { n: 5 }; inc(obj); console.dir(obj);`

## Типы объектов

1. Создайте массив, содержащий названия различных типов данных, в качестве элементов,
пример: `['number', 'string', 'number']`
2. Создайте объект-коллекцию с именами типов в виде ключей и `0` в качестве значения,
пример: `{ number: 0, string: 0 }` и так далее для всех типов данных.
3. Пройдитесь по массиву циклом `for..of` и для каждого элемента массива, увеличивайте
соответствующее значение в объекте-коллекции.
4. Измените пример: удалите все ключи из начальной коллекции и добавляйте их 
динамически используя цикл.