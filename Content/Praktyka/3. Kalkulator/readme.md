# Kalkulator

## Kod

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulator</title>
</head>
<body style="height: 100vh; display: grid; place-items: center;">
<div>
    <label for="number1">Liczba 1:</label>
    <input type="number" name="number1" id="number1">
    <label for="number2">Liczba 2:</label>
    <input type="number" name="number2" id="number2">
    <button id="button" onClick="dodaj()">Dodaj</button>
    <button id="button" onClick="odejmij()">odejmij</button>
    <button id="button" onClick="pomnoz()">Pomnóż</button>
    <div id="wynik"></div>
    <script>
        const dodaj = () => {
            const number1 = parseInt(document.getElementById('number1').value);
            const number2 = parseInt(document.getElementById('number2').value);
            const wynik = number1 + number2;
            document.getElementById('wynik').innerHTML = "Wynik dodawania: " + wynik;
        }

        const odejmij = () => {
            const number1 = parseInt(document.getElementById('number1').value);
            const number2 = parseInt(document.getElementById('number2').value);
            const wynik = number1 - number2;
            document.getElementById('wynik').innerHTML = "Wynik odejmoawania: " + wynik;
        }

        const pomnoz = () => {
            const number1 = parseInt(document.getElementById('number1').value);
            const number2 = parseInt(document.getElementById('number2').value);
            const wynik = number1 * number2;
            document.getElementById('wynik').innerHTML = "Wynik mnożenia: " + wynik;
        }
    </script>
</div>
</body>
</html>
```

## Wynik

![Zmiana koloru](./img.png)
