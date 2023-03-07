# Loops

#### Loopar är praktiska, om du vill köra samma kod om och om igen, var och en tid med ett annat värde.

#### Ofta är detta fallet när man arbetar med arrays:

##### Istället för att skriva:

```
text += fruits[0] + "<br>";
text += fruits[1] + "<br>";
text += fruits[2] + "<br>";
text += fruits[3] + "<br>";
text += fruits[4] + "<br>";
```

##### Skriver du det här:

```
for (let i = 0; i < fruits.length; i++) {
  text += fruits[i] + "<br>";
}
```

JavaScript stöder olika typer av loopar:

```
for
for/in
for/of
while
do/while
```

---

#### For-slingan

Satsen `for` skapar en loop med 3 valfria uttryck: 

```
for (expression 1; expression 2; expression 3) {
  // Kod block som ska köras
}
```

> Uttryck 1 körs (en gång) före körningen av kodblocket.
> Uttryck 2 definierar villkoret för att köra kodblocket.
> Uttryck 3 körs (varje gång) efter att kodblocket har körts.

```
for (let i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```

Från exemplet ovan kan du läsa:

> Uttryck 1 anger en variabel innan slingan startar (let i = 0).
> Uttryck 2 definierar villkoret för att slingan ska köras (måste vara mindre än 5).
> Uttryck 3 ökar ett värde (i++) varje gång kodblocket i loopen har avrättats.

#### <a href="/README.md">![JavaScript](https://img.shields.io/badge/JavaScript-⬅️-332c00?style=for-the-badge&logo=JavaScript)</a>
