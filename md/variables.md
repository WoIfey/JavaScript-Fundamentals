# Variables

#### Variabler är behållare för lagring av data

Det finns fyra olika sätt att deklarera en variabel.

```
var
let
const
Ingenting
```

### Exempel

Allt gör samma sak men använder olika sätt

```
var x = 2;
var y = 2;
var z = x + y;
```

```
let x = 3;
let y = 3;
let z = x + y;
```

```
x = 4;
y = 4;
z = x + y;
```

#### När ska man använda var eller let?

> Nyckelordet `var` används inte längre och nu använder vi `let` och `const`
> Om du vill att din kod ska köras i äldre webbläsare använder du `var`

#### När ska man använda const?

> Deklarera alltid variabler med `const`
> Om du tror att värdet på variablen kan ändras använder du `let`

```
const price1 = 5;
const price2 = 6;
let total = price1 + price2;
```

I det här exempeln ska `const` inte ändras
Men `let` kommer att ändras

#### <a href="/README.md">![JavaScript](https://img.shields.io/badge/JavaScript-⬅️-332c00?style=for-the-badge&logo=JavaScript)</a>
