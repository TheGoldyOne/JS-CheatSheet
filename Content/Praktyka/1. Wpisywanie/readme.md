# Wpisywanie

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
      <input type="text" name="name" id="name" placeholder="Wpisz swoje imię" />
      <button id="button">Wpisz</button>
      <div id="wynik"></div>
      <script>
        const button = document.getElementById("button");
        const name = document.getElementById("name");
        button.addEventListener("click", function () {
          document.getElementById("wynik").innerHTML = "Witaj " + name.value;
        });
      </script>
    </div>
  </body>
</html>
```

## Wynik

![Zmiana koloru](./img.png)
