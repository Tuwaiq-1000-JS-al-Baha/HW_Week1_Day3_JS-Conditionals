# HW_Week1_Day3_JS-Conditionals

### RainDrop Function

Write a function that accepts an argument of a number

If the number contains 3 as a factor, output 'Pling'.

If the number contains 5 as a factor, output 'Plang'.

If the number contains 7 as a factor, output 'Plong'.

If the number does not contain 3, 5, or 7 as a factor, output the number as a string.

```js
rainDrop(28) // Plong
rainDrop(1755) // PlingPlang
rainDrop(34) // 34
```

## Bonus: Golf

Write an if statement that gives a user the nickname of their score, based on par.

| Score      | Nickname       |
| ---------- | -------------- |
| 1          | "Hole in one"  |
| <= par - 2 | "Eagle"        |
| par - 1    | "Birdie        |
| par        | "Par"          |
| par + 1    | "Bogey"        |
| par + 2    | "Double Bogey" |
| >= par + 3 | "Not sure"     |

* Hint:
par is when you get a score of 5.
