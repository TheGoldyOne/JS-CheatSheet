# Pole trójkąta

## Kod

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body style="height: 100vh; display: grid; place-items: center">
    <div>
      <label for="wysokosc">Wysokość: </label>
      <input type="number" name="wysokosc" id="wysokosc" />
      <label for="podstawa">Podstawa: </label>
      <input type="number" name="podstawa" id="podstawa" />
      <button id="button" onClick="oblicz()">Oblicz</button>
      <div id="wynik"></div>
      <script>
        const oblicz = () => {
          const wysokosc = document.getElementById("wysokosc").value;
          const podstawa = document.getElementById("podstawa").value;
          const wynik = (wysokosc * podstawa) / 2;
          document.getElementById("wynik").innerHTML =
            "Pole trójkąta wynosi: " + wynik;
        };
      </script>
    </div>
  </body>
</html>
```

## Wynik

![Zmiana koloru](./img.png)
