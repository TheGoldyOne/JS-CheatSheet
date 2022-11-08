# Zmienne

Dane jakie zmienne przyjmują w JavaScript

Typ zmiennej | Opis
------------ | -------------
|`var` | Można zmieniać jej wartości do woli a odwoływanie się do niej jest możliwe w całym skrypcie|
|`let` | Można zmieniać jej wartości do woli a odwoływanie się do niej jest możliwe w danym bloku skryptu w którym jest zamknięta|
|`const` | Po deklaracji zmiennej nie da się zmienić jej wartości|

## Wartości jakie może przyjmować zmienna

Zmienna | Opis | Przykład
| ----------- | ----------- | ----------- |
|String | Zwykły tekst który zamykamy w cudzysłowach lub apostrofach | let myVariable = 'Bob';|
|Number | Liczba której nie zapisujemy w cudzysłowach | let myVariable = 10;|
|Boolean | Zmienna przechowująca wartośći typu Prawda / Fałsz | let myVariable = true;|
|Array | Tablica która umożliwia przechowywanie wielu obiektów | let myVariable = [1,'Bob','Steve',10];|
|Object | To może być wszystko. Wszystko w JavaScript jest obiektem i może być przechowywane w zmiennej. | let myVariable = document.querySelector('h1');|
> [Link do MDN po Angielsku](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## Const

![meme](./img.png)

> `foo` nadal zawiera "Dobry Wieczór" ale nie da się jej zmienić

## Let

Poniżej przykład kodu w którym nie powinniśmy używać let:

```js
for (let i = 1; i <= 5; i++) {
  let foo = i
}

console.log(foo) // undefined
```

> nie mam pojęcia kto napisałby ten kod ale niech zostanie na potrzeby przykładu

## Var

Ten sam dziwny kod ale z var:

```js
for (let i = 1; i <= 5; i++) {
  var foo = i
}

console.log(foo) // 5
```

> tym razem kod zadziałał bo `var` jest globalny
