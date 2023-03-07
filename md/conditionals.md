# Conditionals

#### Mycket ofta när du skriver kod vill du utföra olika åtgärder för olika beslut

---

### Exempel

Använd satsen för att ange ett block med JavaScript-kod som ska köras om ett villkor är sant `if`

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

Det här anger nya villkor om det första villkoret är falskt `else if`

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

#### <a href="/README.md">![JavaScript](https://img.shields.io/badge/JavaScript-⬅️-332c00?style=for-the-badge&logo=JavaScript)</a>
