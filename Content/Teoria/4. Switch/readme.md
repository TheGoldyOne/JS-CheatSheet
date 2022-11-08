# Switch

Switch służy do sprawdzania wielu warunków. Jest to alternatywa dla wielu ifów.

```js
switch (wyrażenie) {
  case wartość1:
    // kod który się wykona
    break
  case wartość2:
    // kod który się wykona
    break
  default:
    // kod który się wykona
}
```

Przykład:

```js
const day = 1

switch(day) {
    case 1:
        console.log('Poniedziałek')
        break
    case 2:
        console.log('Wtorek')
        break
    case 3:
        console.log('Środa')
        break
    case 4:
        console.log('Czwartek')
        break
    case 5:
        console.log('Piątek')
        break
    case 6:
        console.log('Sobota')
        break
    case 7:
        console.log('Niedziela')
        break
    default:
        console.log('Nie ma takiego dnia')
}

// Wypisze: Poniedziałek
```
