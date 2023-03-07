# Conditionals

#### Mycket ofta när du skriver kod vill du utföra olika åtgärder för olika beslut

### Exempel

Använd `if` satsen för att ange ett block med JavaScript-kod som ska köras om ett villkor är sant

```
if (condition) {
  // Kod som ska köras om condition är sant
}
```

Om det är sant så körs "Too many fruits!", annars "Enough fruits!" `else`

```
const fruits = 5;
let fruit;

if (fruits > 10) {
  fruit = "Too many fruits!";
} else {
  fruit = "Enough fruits!"
}
```

`else if` anger nya villkor om det första villkoret är falskt

```
if (fruits > 10) {
  fruit = "Too many fruits!";
} else if (fruits == 5) {
  fruit = "Just the right amount of fruits!";
} else {
  fruit = "Enough fruits!"
}
```

---

Uttalandet `switch` används för att utföra olika åtgärder baserat på olika förhållanden

```
switch(expression) {
  case x:
    // Kod block
    break;
  case y:
    // Kod block
    break;
  default:
    // Kod block
}
```

Så här går det till:

- `Switch` används en gång.
- Värdet på uttrycket jämförs med värdena för varje enskilt `case`.
- Om det finns en matchning körs det associerade kodblocket.
- Om det inte finns någon matchning körs standardkodblocket.

---

Metoden `getDay()` returnerar veckodagen som ett tal mellan 0 och 6

(Söndag = 0, Måndag = 1, Tisdag = 2 ...)

I det här exemplet används veckodagsnumret för att beräkna veckodagsnamnet:

```
switch (new Date().getDay()) {
  case 0:
    day = "Sunday";
    break;
  case 1:
    day = "Monday";
    break;
  case 2:
     day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
}
```

#### <a href="/README.md">![JavaScript](https://img.shields.io/badge/JavaScript-⬅️-332c00?style=for-the-badge&logo=JavaScript)</a>
