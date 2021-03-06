# Задание №1 (не код)

Почему символьные константы лучше литеральных (магических чисел)? Почему использование const лучше использования директив #define?

## Ответ

> чес слово, написал до того, как прочёл ответ на сайте.. потом чуток подправил.. 👽

Прежде всего, компилятор не воспринимает литеральные константы как таковые,
но лишь заменяет их на их значения, тогда как символьные константы компилятор
воспринимает почти как символьные переменные (удивительно, не так ли?).

Таким образом, компилятор лучше понимает, что он имеет дело с константой, а не
с её значением. Следовательно, процесс разработки упрощается, так как вместе
с разработчиком константы видит и компилятор, и дебаггер, и прочие.

Компилятор явно повнимательнее многих разработчиков, не будет лишним доверить
ему немного констант.