# Сумма прописью на JavaScript

> Запись суммы прописью. Денежная единица - рубль

![screenshot](/screenshot.png)

### [Демо]

## Описание
Основной целью при написании являлось изобретение алгоритма, не основанного на математических действиях над заданным числом, а представлением его строковым значением с последующим посимвольным разбором.

## Использование

Для работы необходимо подключить файл num2str.js

```html
<script src="/path/to/num2str.js"></script>
```

Пример использования на странице:

```html
Сумма:
<input type="text" onKeyUp="num2str(this.value, 'str')" />

Прописью:
<div id="str"></div>
```

Функция `num2str` имеет два параметра. Первый - число для преобразования, второй - `id` элемента для вывода результата. Так уж сложилось на момент написания 2005 году.

**Особенности**

- алгоритм написан «с нуля» (все совпадения считать совпадениями)
- легко расширяется до триллионов и больших значений
- нет принципиальной привязки к рублям (может работать с другими денежными единицами)
- исключено появление лишних пробелов
- знак-разделитель для копеек — «.» или «,»
- минимум математики


## Демо

**Для локального запуска**


```sh
$ git clone https://github.com/mad48/num-words.git
```


Открыть в браузере файл index.html.

Лицензия
----

[MIT](http://www.opensource.org/licenses/mit-license.php)

[//]: #

[Демо]: <https://mad48.github.io/num-words/index.html>
