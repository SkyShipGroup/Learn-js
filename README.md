# learn javascript 

## введния 
**ну значит, первое что вам нужно: установка `node js` на компьютер. или же кодить в https://replit.com**

# переменные

**есть несколько вариантов записи переменных.**

**Переменные в JavaScript являются основными элементами языка программирования, которые используются для хранения данных и значений в памяти компьютера. Они могут содержать различные типы данных, такие как числа, строки, булевы значения и объекты.**

**В JavaScript переменные могут быть объявлены с помощью ключевых слов** `var`, `let` **или** `const`. **Ключевое слово var использовалось ранее для объявления переменных, но сейчас рекомендуется использовать** `let и const.`

**Синтаксис для объявления переменной `let` выглядит так:**

```
let имя_переменной = значения
```
**Например, чтобы объявить переменную с именем `x` и присвоить ей значение `5`, вы можете написать следующий код:**

```
let x = 5;
```
**Ключевое слово `const` используется для объявления констант, то есть переменных, которые не могут быть изменены после их объявления. Синтаксис для объявления константы выглядит так:**

```
const имя_переменной = значения
```
### принцепи как и во всех других.

**Например вы хотите обьявить константу `PI` и присвоить ему число `3.14`.**

```
const PI = 13.4
```

**Если например не хотите присваивать сейчас какое значения, оно по дефолту будет `undefined`.**

```
let z;
z = 10
```

**переменные довольно гибкий инструмент для храния данных, но сразу после первого перезапуска кода она уничтожится ибо выполнит свою работу, это не значит что оно пропадет, если вы будете использовать что то что принимает данные то после первого перезапуска значения к своему изначальному.**
```
let i;
```