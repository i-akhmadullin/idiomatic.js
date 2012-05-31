# Принципы написания последовательного, выразительного JavaScript

## Эти принципы постоянно дополняются, новые идеи и предложения по улучшению всячески приветствуются. Внесите свой вклад в развитие любым образом: fork, clone, branch, commit, push, pull request.

* Rick Waldron [@rwaldron](http://twitter.com/rwaldron), [github](https://github.com/rwldrn)
* Mathias Bynens [@mathias](http://twitter.com/mathias), [github](https://github.com/mathiasbynens)
* Schalk Neethling [@ossreleasefeed](http://twitter.com/ossreleasefeed), [github](https://github.com/ossreleasefeed/)
* Kit Cambridge  [@kitcambridge](http://twitter.com/kitcambridge), [github](https://github.com/kitcambridge)
* Raynos  [github](https://github.com/Raynos)
* Matias Arriola [@MatiasArriola](https://twitter.com/MatiasArriola), [github](https://github.com/MatiasArriola/)
* John Fischer [@jfroffice](https://twitter.com/jfroffice), [github](https://github.com/jfroffice/)
* Idan Gazit [@idangazit](http://twitter.com/idangazit), [github](https://github.com/idangazit)
* Leo Balter [@leobalter](http://twitter.com/leobalter), [github](https://github.com/leobalter)
* Breno Oliveira [@garu_rj](http://twitter.com/garu_rj), [github](https://github.com/garu)
* Leo Beto Souza [@leobetosouza](http://twitter.com/leobetosouza), [github](https://github.com/leobetosouza)
* Ryuichi Okumura [@okuryu](http://twitter.com/okuryu), [github](https://github.com/okuryu)
* Pascal Precht [@PascalPrecht](http://twitter.com/PascalPrecht), [github](https://github.com/pascalprecht)
* EngForDev [engfordev](http://www.opentutorials.org/course/167/1363) - Hwan Min Hong / MinTaek Kwon [@leoinsight](http://twitter.com/leoinsight) / Tw Shim [@marocchino](http://twitter.com/marocchino), [github](https://github.com/marocchino) / Nassol Kim [@nassol99](http://twitter.com/nassol99), [github](https://github.com/nassol) / Juntai Park [@rkJun](http://twitter.com/rkJun), [github](https://github.com/rkJun) / Minkyu Shim / Gangmin Won / Justin Yoo [@justinchronicle](http://twitter.com/justinchronicle) / Daeyup Lee
* Marco Trulla [@marcotrulla](http://twitter.com/marcotrulla), [github](https://github.com/Ragnarokkr)
* Akhmadullin Ilia [@i_akhmadullin](http://twitter.com/i_akhmadullin), [github](https://github.com/i-akhmadullin)

## Весь код, в любой его части должен выглядеть так, как если бы его написал один человек, независимо от количества людей, работавших над проектом.

### Следующий список даёт представление о принципах, которыми я руководствуюсь во всем коде, в котором являюсь автором. Все дополнения в мои проекты, должны следовать принципам этого руководства.

### Я не навязываю мои предпочтения к оформлению кода другим, если у них есть существующий набор правил - это надо уважать.

> "Part of being a good steward to a successful project is realizing that writing code for yourself is a Bad Idea™. If thousands of people are using your code, then write your code for maximum clarity, not your personal preference of how to get clever within the spec." - Idan Gazit


## Переводы

* [Оригинал](https://github.com/rwldrn/idiomatic.js)
* [German](https://github.com/rwldrn/idiomatic.js/tree/master/translations/de_DE)
* [French](https://github.com/rwldrn/idiomatic.js/tree/master/translations/fr_FR)
* [Spanish](https://github.com/rwldrn/idiomatic.js/tree/master/translations/es_ES)
* [Portuguese - Brazil](https://github.com/rwldrn/idiomatic.js/tree/master/translations/pt_BR)
* [Korean](https://github.com/rwldrn/idiomatic.js/tree/master/translations/ko_KR)
* [Japanese](https://github.com/rwldrn/idiomatic.js/tree/master/translations/ja_JP)
* [Italian](https://github.com/rwldrn/idiomatic.js/tree/master/translations/it_IT)

## Важное, но второстепенное:

### Качество кода: отличные утилиты, ресурсы и ссылки

 * [jsPerf](http://jsperf.com/)
 * [jsFiddle](http://jsfiddle.net/)
 * [jsbin](http://jsbin.com/)
 * [JavaScript Lint (JSL)](http://javascriptlint.com/)
 * [jshint](http://jshint.com/)
 * [jslint](http://jslint.org/)

[Leveraging Code Quality Tools by Anton Kovalyov](http://anton.kovalyov.net/slides/gothamjs/)


### Самообразование

[http://es5.github.com/](http://es5.github.com/)

Следующий список книг надо считать 1) неполным 2) *ТРЕБУЮЩИМ ВЫЧИТКИ*. Я не всегда соглашаюсь со стилем, который предлагают авторы книг, перечисленных ниже, но среди них всех важна одна вещь: они последовательны. Кроме того, они считаются авторитетами по Яваскрипту.

 * [Baseline For Front End Developers](http://rmurphey.com/blog/2012/04/12/a-baseline-for-front-end-developers/)
 * [Eloquent JavaScript](http://eloquentjavascript.net/)
 * [JavaScript, JavaScript](http://javascriptweblog.wordpress.com/)
 * [Adventures in JavaScript Development](http://rmurphey.com/)
 * [Perfection Kills](http://perfectionkills.com/)
 * [Douglas Crockford's Wrrrld Wide Web](http://www.crockford.com)
 * [JS Assessment](https://github.com/rmurphey/js-assessment)


### Сборка и процесс развертывания 

Авторы проектов всегда должны стараться включать какие-то способы, с помощью которых исходники можно провалидировать, протестировать, сжать для дальнейшего использования в продакшене. Для этой задачи идеально подходит [grunt](https://github.com/cowboy/grunt) за авторством Ben Alman, grunt заменил целую папку "kits/" в этом репозитории.




### Тестирование

Проекты должны включать какую-либо форму модульного(юнит), регрессионого, интеграционного, функционального тестирования. Использование подготовленных демо, НЕ СЧИТАЕТСЯ за тест. Далее следует список фреймворков для тестирования:

 * [QUnit](http://github.com/jquery/qunit)
 * [Jasmine](https://github.com/pivotal/jasmine)
 * [Vows](https://github.com/cloudhead/vows)
 * [Mocha](https://github.com/visionmedia/mocha)
 * [Hiro](http://hirojs.com/)
 * [JsTestDriver](https://code.google.com/p/js-test-driver/)
 * [Buster.js](http://busterjs.org/)

## Содержание

 * [Пробелы](#whitespace)
 * [Красивый синтаксис](#spacing)
 * [Проверка типов](#type)
 * [Условное выполнение](#cond)
 * [Практичный стиль](#practical)
 * [Именование](#naming)
 * [Прочее](#misc)
 * [Native & Host объекты](#native)
 * [Комментарии](#comments)
 * [Единый стиль](#language)



------------------------------------------------


## Предисловие

Следующие разделы описывают список разумных правил для оформление кода для разработки на Яваскрипте, которые могут быть изменены. Самое важное соблюдать **постоянство и последовательность в оформлении кода**. Какие бы правила к офомрлению вы не выбрали, вы должны придерживаться их неукоснительно. Добавляйте ссылку на этот документ, в знак вклада в последовательность, читаемость и простоту поддержки кода.





## Idiomatic Style Manifesto


1. <a name="whitespace">Whitespace</a>
  - Не используйте пробелы и табы одновременно.
  - Перед началом проекта, до того как напишете хоть строчку кода, выберите один из вариантов отбивки кода: пробелами или табами и используйте **только его**.
      - Ради читаемости, я рекомендую настроить размер отступа в редакторе до двух символов &mdash; то есть два пробела равны одному табу.
  - Если ваш редактор поддерживает настройку, показывающую пробельные символы, всегда работайте с ней. Преимущества этой настройки следующие:
      - Более последовательный в оформлении код
      - Устранение пробелов в конце строк
      - Утранение пробелов в пустых строках
      - Легче читать коммиты и диффы в системах контроля версии.


2. <a name="spacing">Красивый синтаксис</a>

    A. Скобки, фигурные скобки, переносы строк

    ```javascript

    // if/else/for/while/try всегда отделяются пробелом, за которым следуют фигурные скобки, которые занимают несколько строк
    // это облегчает чтение кода

    // 2.A.1.1
    // Пример неразборчивого кода

    if(condition) doSomething();

    while(condition) iterating++;

    for(var i=0;i<100;i++) someIterativeFn();


    // 2.A.1.1
    // Используйте пробелы, чтобы улучшить читаемость

    if ( condition ) {
      // код
    }

    while ( condition ) {
      // код
    }

    for ( var i = 0; i < 100; i++ ) {
      // код
    }

    // Еще лучше писать так:

    var i,
      length = 100;

    for ( i = 0; i < length; i++ ) {
      // код
    }

    // Или так...

    var i = 0,
      length = 100;

    for ( ; i < length; i++ ) {
      // код
    }

    var prop;

    for ( prop in object ) {
      // код
    }


    if ( true ) {
      // код
    } else {
      // код
    }
    ```


    B. Присваивание, описание, функции ( именованные, выражения, конструкторы )

    ```javascript

    // 2.B.1.1
    // Переменные
    var foo = "bar",
      num = 1,
      undef;

    // Литералы:
    var array = [],
      object = {};


    // 2.B.1.2
    // Использование только одного `var` на всю область видимости(функцию) улучшает читабельность
    // и уменьшает беспорядок в списке определения переменных (и экономит несколько символов)

    // Неправильно
    var foo = "";
    var bar = "";
    var qux;

    // Правильно
    var foo = "",
      bar = "",
      quux;

    // или..
    var // комментарий...
    foo = "",
    bar = "",
    quux;

    // 2.B.1.3
    // Блок с определением переменных var всегда должен быть в начале области видимости(scope) или функции.
    // Тоже самое справедливо для const и let из ECMAScript 6.

    // Неправильно
    function foo() {

      // код 

      var bar = "",
        qux;
    }

    // Правильно
    function foo() {
      var bar = "",
        qux;

      // код, следующий после блока с определением переменных.
    }
    ```

    ```javascript

    // 2.B.2.1
    // Определение именованной функции
    function foo( arg1, argN ) {

    }

    // Использование
    foo( arg1, argN );


    // 2.B.2.2
    // Определение именованной функции
    function square( number ) {
      return number * number;
    }

    // Использование
    square( 10 );

    // Очень надуманный пример с передачей параметров
    function square( number, callback ) {
      callback( number * number );
    }

    square( 10, function( square ) {
      // код коллбэка
    });


    // 2.B.2.3
    // Функция
    var square = function( number ) {
      // возвращает что-нибудь важное и нужное
      return number * number;
    };

    // Функционально выражение с идентификатором
    // Эта рекомендуемая форма, хороша тем, что может вызывать сама себя
    // и тем что у нее будет уникальное имя в отладчике браузера:
    var factorial = function factorial( number ) {
      if ( number < 2 ) {
        return 1;
      }

      return number * factorial( number-1 );
    };


    // 2.B.2.4
    // Объявление конструктора
    function FooBar( options ) {

      this.options = options;
    }

    // Использование
    var fooBar = new FooBar({ a: "alpha" });

    fooBar.options;
    // { a: "alpha" }

    ```


    C. Некоторые исключения из правил

    ```javascript

    // 2.C.1.1
    // Функции с обратным вызовом
    foo(function() {
      // Заметьте после первой скобки перед словом 
      // "function" нет пробела
    });

    // Функция, принимающая массив, без пробела после круглой скобки
    foo([ "alpha", "beta" ]);

    // 2.C.1.2
    // Функция, принимающая объект, без пробела после круглой скобки
    foo({
      a: "alpha",
      b: "beta"
    });

    // Единичный строковый аргумент, также без пробелов
    foo("bar");

    // Вложенные скобки для группировки, без пробелов
    if ( !("foo" in obj) ) {

    }

    ```

    D. Постоянность прежде всего

    В разделах 2.A-2.C, правила для пробельных символов установлены с одной целью: последовательность в оформлении кода.
    Важно заметить, что такие предпочтения к форматированию кода, как "внутренние пробелы" надо считать необязательными, тем не менее во всем проекте должен быть только один стиль оформления.

    ```javascript

    // 2.D.1.1

    if (условие) {
      // код
    }

    while (условие) {
      // код
    }

    for (var i = 0; i < 100; i++) {
      // код
    }

    if (true) {
      // код
    } else {
      // код
    }

    ```

    E. Кавычки

    Неважно какие кавычки вам больше нравятся, нет никакой разницы в том как Яваскрипт парсит их. Чего надо **АБСОЛЮТНО ПРИДЕРЖИВАТЬСЯ** так это последовательности оформления. **Никогда не используйте разные кавычки в одном проекте. Выберите один стиль и придерживайтесь его.**

    F. Окончание строк и пустые строки

    Пробелы могут испортить diff'ы и сделать просмотр изменений практически невозможным. Постарайтесь добавить pre-commit хук, который будет автоматически удалять пробельные символы в конце строк, пробелы в пустых строках.

3. <a name="type">Проверка типов (Заимствовано из гайдлайнов по стилю jQuery Core)</a>

    A. Типы

    String:

        typeof variable === "string"

    Number:

        typeof variable === "number"

    Boolean:

        typeof variable === "boolean"

    Object:

        typeof variable === "object"

    Array:

        Array.isArray( arrayLikeObject )
        (когда возможно)

    Node:

        elem.nodeType === 1

    null:

        variable === null

    null или undefined:

        variable == null

    undefined:

      Глобальные переменные:

        typeof variable === "undefined"

      Локальные переменные:

        variable === undefined

      Свойства:

        object.prop === undefined
        object.hasOwnProperty( prop )
        "prop" in object

    B. Неявное приведение типов

    Представьте результат следующего...

    Дан такой HTML:

    ```html

    <input type="text" id="foo-input" value="1">

    ```


    ```javascript

    // 3.B.1.1

    // переменная `foo` была определена со значением `0`, ее тип `number`
    var foo = 0;

    // typeof foo;
    // "number"
    ...

    // Далее в коде, вам нужно присвоить `foo`
    // новое значение из поля ввода

    foo = document.getElementById("foo-input").value;

    // Если теперь проверить `typeof foo`, результат будет `string`
    // Это значит, что если было бы условие, которое тестировало значение `foo` таким образом:

    if ( foo === 1 ) {

      importantTask();

    }

    // функция `importantTask()` не была бы вызвана, хотя значение `foo` равно "1"


    // 3.B.1.2

    // Можно предотвратить такие проблемы, если использовать "умное" приведение типов с использованием унарных операторов + или - :

    foo = +document.getElementById("foo-input").value;
    //    ^ унарный оператор + переводит тип операнда справа от него в number

    // typeof foo;
    // "number"

    if ( foo === 1 ) {

      importantTask();

    }

    // в этом случае `importantTask()` будет вызвана
    ```

    Ниже приведены примеры с "умным" приведением типов:


    ```javascript

    // 3.B.2.1

    var number = 1,
      string = "1",
      bool = false;

    number;
    // 1

    number + "";
    // "1"

    string;
    // "1"

    +string;
    // 1

    +string++;
    // 1

    string;
    // 2

    bool;
    // false

    +bool;
    // 0

    bool + "";
    // "false"
    ```


    ```javascript
    // 3.B.2.2

    var number = 1,
      string = "1",
      bool = true;

    string === number;
    // false

    string === number + "";
    // true

    +string === number;
    // true

    bool === number;
    // false

    +bool === number;
    // true

    bool === string;
    // false

    bool === !!string;
    // true
    ```

    ```javascript
    // 3.B.2.3

    var array = [ "a", "b", "c" ];

    !!~array.indexOf("a");
    // true

    !!~array.indexOf("b");
    // true

    !!~array.indexOf("c");
    // true

    !!~array.indexOf("d");
    // false

    // Последние примеры, надо считать "слишком умными"
    // Отдавайте предпочтение более очевидным методам сравнения значения
    // indexOf, например:

    if ( array.indexOf( "a" ) >= 0 ) {
      // ...
    }
    ```

    ```javascript
    // 3.B.2.3


    var num = 2.5;

    parseInt( num, 10 );

    // тоже самое что и...

    ~~num;

    num >> 0;

    num >>> 0;

    // Все эти способы возращают 2


    // Тем не менее не забывайте, что отрицательные значения будут обрабатываются по-другому...

    var neg = -2.5;

    parseInt( neg, 10 );

    // тоже самое что и...

    ~~neg;

    neg >> 0;

    // Все равны -2
    // Однако...

    neg >>> 0;

    // Будет равно 4294967294




    ```



4. <a name="cond">Условное выполнение</a>

    ```javascript

    // 4.1.1
    // Когда определяете, есть ли у массива длина,
    // вместо этого:
    if ( array.length > 0 ) ...

    // ...проверяйте значение на правдивость, например так:
    if ( array.length ) ...


    // 4.1.2
    // Когда определяете, пустой ли массив,
    // вместо этого:
    if ( array.length === 0 ) ...

    // ...проверяйте значение на правдивость, например так:
    if ( !array.length ) ...


    // 4.1.3
    // Когда определяете, что строка не пустая,
    // вместо этого:
    if ( string !== "" ) ...

    // ...проверяйте значение на правдивость, например так:
    if ( string ) ...


    // 4.1.4
    // Когда определяете, что строковая переменная равна пустой строке,
    // вместо этого:
    if ( string === "" ) ...

    // ...проверяйте значение на лживость, например так:
    if ( !string ) ...


    // 4.1.5
    // Когда определяете, что значение переменной равно true,
    // вместо этого:
    if ( foo === true ) ...

    // ...используйте, встроенную в язык возможность:
    if ( foo ) ...


    // 4.1.6
    // Когда определяете, что значение переменной равно false,
    // вместо этого:
    if ( foo === false ) ...

    // ...используйте отрицание, чтобы получить нужный результат
    if ( !foo ) ...

    // ...Будьте осторожны, этот метод сработает для следующих значений: 0, "", null, undefined, NaN
    // Если вы _ДОЛЖНЫ_ проверить на булевую ложь, тогда используйте
    if ( foo === false ) ...


    // 4.1.7
    // Когда определяете, что значение переменной может быть null или undefined, но НЕ РАВНО false, "" или 0,
    // вместо этого:
    if ( foo === null || foo === undefined ) ...

    // ...используйте приведение типов оператора == например так:
    if ( foo == null ) ...

    // Помните, что `== null` правдиво для ДВУХ значений `null` и `undefined`
    // но не для `false`, "" or 0
    null == undefined

    ```
    ВСЕГДА используйте проверки, подходящие для вашего конкретного случая, чтобы получить лучший, наиболее точный результат. Приемы, указанные выше - руководство, а не догма.

    ```javascript

    // 4.2.1
    // Замечания о приведении типов и сравнении

    // Предпочитайте `===` вместо `==` (только если ваш случай приемлет менее строгое приведение типов)

    // === не использует приведение типов, таким образом:

    "1" === 1;
    // false

    // == использует приведение типов, таким образом:

    "1" == 1;
    // true


    // 4.2.2
    // Логические переменные, правдивость и лживость

    // Логические переменные:
    true, false

    // Правдивы:
    "foo", 1

    // Ложны:
    "", 0, null, undefined, NaN, void 0

    ```


5. <a name="practical">Практичный стиль</a>

    ```javascript

    // 5.1.1
    // Практичный модуль

    (function( global ) {
      var Module = (function() {

        var data = "secret";

        return {
          // Некоторая логическая переменная
          bool: true,
          // Строковое значение
          string: "a string",
          // Массив
          array: [ 1, 2, 3, 4 ],
          // Объект
          object: {
            lang: "en-Us"
          },
          getData: function() {
            // возращает текущее значение `data`
            return data;
          },
          setData: function( value ) {
            // устанавливает новое значение `data` на `value` и возвращает его
            return ( data = value );
          }
        };
      })();

      // Остальной код

      // делаем модуль видимым в объекте global
      global.Module = Module;

    })( this );

    ```

    ```javascript

    // 5.2.1
    // Практичный конструктор

    (function( global ) {

      function Ctor( foo ) {

        this.foo = foo;

        return this;
      }

      Ctor.prototype.getFoo = function() {
        return this.foo;
      };

      Ctor.prototype.setFoo = function( val ) {
        return ( this.foo = val );
      };


      // Вызвать конструктор без `new`, можно так:
      var ctor = function( foo ) {
        return new Ctor( foo );
      };


      // делаем видимым конструктор в объекте global
      global.ctor = ctor;

    })( this );

    ```



6. <a name="naming">Именование</a>



    A. Вы не должны выполнять работу за компилятора/обфускатора ресурсов.

    Пример вопиющего именования:

    ```javascript

    // 6.A.1.1
    // Код с плохими именами переменных

    function q(s) {
      return document.querySelectorAll(s);
    }
    var i,a=[],els=q("#foo");
    for(i=0;i<els.length;i++){a.push(els[i]);}
    ```

    Без сомнения, вы писали подобный код, надеемся, что начиная с сегодняшнего дня, больше не будете.

    Тот же самый код, но с более осмысленным именованием (и более читаемой структурой):

    ```javascript

    // 6.A.2.1
    // Пример кода с улучшенными именами переменных

    function query( selector ) {
      return document.querySelectorAll( selector );
    }

    var idx = 0,
      elements = [],
      matches = query("#foo"),
      length = matches.length;

    for ( ; idx < length; idx++ ) {
      elements.push( matches[ idx ] );
    }

    ```

    Еще несколько замечаний по именованию:

    ```javascript

    // 6.A.3.1
    // Именование строк

    `dog` - строка


    // 6.A.3.2
    // Именование массивов

    `dogs` - массив строк `dog` 


    // 6.A.3.3
    // Именование функций, объектов, экземпляров, и тп.

    camelCase; для названий функций и определений переменных через var


    // 6.A.3.4
    // Именование конструкторов, прототипов, и тп.

    PascalCase; для названий конструкторов


    // 6.A.3.5
    // Именование регулярных выражений

    rDesc = //;


    // 6.A.3.6
    // Из руководства по стилю Google Closure Library

    functionNamesLikeThis;
    variableNamesLikeThis;
    ConstructorNamesLikeThis;
    EnumNamesLikeThis;
    methodNamesLikeThis;
    SYMBOLIC_CONSTANTS_LIKE_THIS;

    ```

    B. Многоликий `this`

    Кроме широко известных применений `call` и `apply`, всегда старайтесь использовать `.bind( this )` или его функциональный эквивалент, чтобы создавать `BoundFunction` для дальнейших вызовов. Прибегайте к псевдонимам, только когда нет других вариантов.

    ```javascript

    // 6.B.1
    function Device( opts ) {

      this.value = null;

      // открываем асинхронный поток stream,
      // это будет вызываться постоянно
      stream.read( opts.path, function( data ) {

        // Обновляем текущее значение экземпляра
        // на последнее значение из 
        // потока data
        this.value = data;

      }.bind(this) );

      // Контролируем частоту событий, которые испускает
      // экземпляр Device
      setInterval(function() {

        // Выпускаем событие
        this.emit("event");

      }.bind(this), opts.freq || 100 );
    }

    // Представим, что здесь мы унаследовались от EventEmitter ;)

    ```

    Если нет возможности использовать `.bind`, для него есть замена в большинстве современных библиотек на JavaScript.


    ```javascript
    // 6.B.2

    // пример lodash/underscore, _.bind()
    function Device( opts ) {

      this.value = null;

      stream.read( opts.path, _.bind(function( data ) {

        this.value = data;

      }, this) );

      setInterval(_.bind(function() {

        this.emit("event");

      }, this), opts.freq || 100 );
    }

    // пример jQuery.proxy
    function Device( opts ) {

      this.value = null;

      stream.read( opts.path, jQuery.proxy(function( data ) {

        this.value = data;

      }, this) );

      setInterval( jQuery.proxy(function() {

        this.emit("event");

      }, this), opts.freq || 100 );
    }

    // пример dojo.hitch
    function Device( opts ) {

      this.value = null;

      stream.read( opts.path, dojo.hitch( this, function( data ) {

        this.value = data;

      }) );

      setInterval( dojo.hitch( this, function() {

        this.emit("event");

      }), opts.freq || 100 );
    }

    ```

    На крайний случай создайте ссылку на `this` используя `self` в качестве названия. Этот способ сильно подтвержден ошибкам, его надо избегать насколько возможно.

    ```javascript

    // 6.B.3

    function Device( opts ) {
      var self = this;

      this.value = null;

      stream.read( opts.path, function( data ) {

        self.value = data;

      });

      setInterval(function() {

        self.emit("event");

      }, opts.freq || 100 );
    }

    ```


    C. Использование `thisArg`

    В некоторых встроенных методах прототипов из ES 5.1 есть специальная сигнатура `thisArg`, которую надо использовать когда это возможно

    ```javascript

    // 6.C.1

    var obj;

    obj = { f: "foo", b: "bar", q: "qux" };

    Object.keys( obj ).forEach(function( key ) {

      // |this| теперь ссылается на `obj`

      console.log( this[ key ] );

    }, obj ); // <-- последний аргумент `thisArg`

    // Вывод...

    // "foo"
    // "bar"
    // "qux"

    ```

    `thisArg` можно использовать с `Array.prototype.every`, `Array.prototype.forEach`, `Array.prototype.some`, `Array.prototype.map`, `Array.prototype.filter`

7. <a name="misc">Прочее</a>

    Этот раздел существует для выражения идей и принципов, которые нельзя считать догмой. Они упомянуты с целью призвать к обсуждению и поиску способов лучше выполнять стандартные задачи на JavaScript.

    A. Использования `switch` надо избегать, modern method tracing will blacklist functions with switch statements

    Скорость обработки `switch` заметно улучшилась в последних релизах Firefox и Chrome.
    http://jsperf.com/switch-vs-object-literal-vs-module

    Обсуждение по этой теме:
    https://github.com/rwldrn/idiomatic.js/issues/13

    ```javascript

    // 7.A.1.1
    // Пример выражения с switch

    switch( foo ) {
      case "alpha":
        alpha();
        break;
      case "beta":
        beta();
        break;
      default:
        // действия по умолчанию
        break;
    }

    // 7.A.1.2
    // Лучше использовать литерал или модуль:

    var switchObj = {
      alpha: function() {
        // код
        // возвращение результата
      },
      beta: function() {
        // код
        // возвращение результата
      },
      _default: function() {
        // код
        // возвращение результата
      }
    };

    var switchModule = (function () {
      return {
        alpha: function() {
          // код
          // возвращение результата
        },
        beta: function() {
          // код
          // возвращение результата
        },
        _default: function() {
          // код
          // возвращение результата
        }
      };
    })();


    // 7.A.1.3
    // Если `foo` - свойство `switchObj` или `switchModule`, вызывайте его как метод...

    ( Object.hasOwnProperty.call( switchObj, foo ) && switchObj[ foo ] || switchObj._default )( args );

    ( Object.hasOwnProperty.call( switchObj, foo ) && switchModule[ foo ] || switchModule._default )( args );

    // Если вы можете доверять значению `foo`, можно опустить проверку OR
    // останется только вызов:

    switchObj[ foo ]( args );

    switchModule[ foo ]( args );


    // Этот паттерн облегчает повторное использование кода.

    ```

    B. Ранний возврат значения способствует повторному использованию кода плюс дает незаметный выигрыш в производительности

    ```javascript

    // 7.B.1.1
    // Неправильно:
    function returnLate( foo ) {
      var ret;

      if ( foo ) {
        ret = "foo";
      } else {
        ret = "quux";
      }
      return ret;
    }

    // Правильно:

    function returnEarly( foo ) {

      if ( foo ) {
        return "foo";
      }
      return "quux";
    }

    ```


8. <a name="native">Native & Host объекты</a>

    Основной принцип таков:

    ### Не делайте глупостей и все будет впорядке.

    Для лучшего понимания этого принципа, посмотрите видео:

    #### “Everything is Permitted: Extending Built-ins” by Andrew Dupont (JSConf2011, Portland, Oregon)

    <iframe src="http://blip.tv/play/g_Mngr6LegI.html" width="480" height="346" frameborder="0" allowfullscreen></iframe><embed type="application/x-shockwave-flash" src="http://a.blip.tv/api.swf#g_Mngr6LegI" style="display:none"></embed>

    http://blip.tv/jsconf/jsconf2011-andrew-dupont-everything-is-permitted-extending-built-ins-5211542


9. <a name="comments">Комментарии</a>

  * Однострочные комментарии над комментируемой строкой
  * Можно использовать многострочные комментарии
  * Комментарии в конце строк запрещены!
  * Комментарии в стиле JSDoc разрешены, но требуют много времени


10. <a name="language">Единый стиль кода</a>

    Программы должны быть написаны в едином стиле, каким бы он ни был, в стиле, заданном авторами проекта.

## Приложение

### Сначала запятая(Comma First).

Любой проект, который ссылается на этот документ в качестве основы для своего оформления кода не будет использовать форматирование "сначала запятая"(Comma First), если только это не оговорено автором проекта.
