# Arrays

#### En array är en speciell variabel som kan innehålla mer än ett värde:

### Exempel

```
const fruits = ["Apple", "Coconut", "Watermelon", "Banana", "Strawberry"];
```

### Varför använder vi arrays?

Om du har en lista med objekt (till exempel olika frukter) så kan det se ut så här:

```
let fruit1 = "Apple";
let fruit2 = "Coconut";
let fruit3 = "Watermelon";
let fruit4 = "Banana";
let fruit5 = "Strawberry";
```

Det är bättre att använda arrays om du vill hitta en specifik frukt eller om du lagra över till exempel 100 frukter.
En array kan lagra många objekter under ett namn.

---

Mellanslag och radbrytningar är inte viktiga men det kan se bättre med det.

```
const fruits = [
    "Apple",
    "Coconut",
    "Watermelon",
    "Banana",
    "Strawberry"
    ];
```

Du kan också skapa en array och sedan ange elementen:

```
const fruits = [];
fruits[0]= "Apple";
fruits[1]= "Coconut";
fruits[2]= "Watermelon";
```

Du kan också använda nyckelordet "new" för att skapa en ny array

```
const fruits = new Array("Apple", "Coconut", "Watermelon");
```

Du kan få ett arrayelement genom att referera till indexnumret:

```
const fruits = ["Apple", "Coconut", "Watermelon", "Banana", "Strawberry"];
let fruit = fruits[1]; // Coconut
```

#### <a href="/README.md">![JavaScript](https://img.shields.io/badge/JavaScript-⬅️-332c00?style=for-the-badge&logo=JavaScript)</a>
