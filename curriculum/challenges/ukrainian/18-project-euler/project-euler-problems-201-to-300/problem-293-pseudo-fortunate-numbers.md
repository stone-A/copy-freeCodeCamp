---
id: 5900f4931000cf542c50ffa4
title: 'Завдання 293: псевдовезучі числа'
challengeType: 1
forumTopicId: 301945
dashedName: problem-293-pseudo-fortunate-numbers
---

# --description--

Парне натуральне число $N$ називатиметься прийнятним, якщо воно є ступенем 2 або ж його різні прості співмножники є послідовними числами.

Першими дванадцятьма прийнятними числами є 2, 4, 6, 8, 12, 16, 18, 24, 30, 32, 36, 48.

Якщо $N$ є прийнятним, то найменше ціле число $M > 1$, за якого сума $N + M$ буде простим числом, називатиметься псевдовезучим числом для $N$.

Наприклад, $N = 630$ є прийнятним, оскільки воно парне, а його різні прості співмножники є послідовними числами (2, 3, 5 та 7). Наступним простим числом після 631 є 641; тому псевдовезучим числом для 630 є $M = 11$. Також можна довести, що псевдовезучим числом для 16 є 3.

Знайдіть суму всіх різних псевдовезучих чисел для прийнятних чисел $N$, менших за ${10}^9$.

# --hints--

`pseudoFortunateNumbers()` має повернути `2209`.

```js
assert.strictEqual(pseudoFortunateNumbers(), 2209);
```

# --seed--

## --seed-contents--

```js
function pseudoFortunateNumbers() {

  return true;
}

pseudoFortunateNumbers();
```

# --solutions--

```js
// solution required
```
