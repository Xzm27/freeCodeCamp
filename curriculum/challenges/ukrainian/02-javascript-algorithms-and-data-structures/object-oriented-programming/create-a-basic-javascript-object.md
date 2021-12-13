---
id: 587d7dac367417b2b2512b73
title: Створення базового об'єкту JavaScript
challengeType: 1
forumTopicId: 301317
dashedName: create-a-basic-javascript-object
---

# --description--

Подумайте про речі, що оточують людей щодня. До прикладу, машини, крамниці, птахи. Вони є <dfn>об'єктами</dfn>: реальними речами, за якими можна як спостерігати, так і взаємодіяти з ними.

Якими є якості цих об'єктів? Машина має колеса. В крамниці продають продукти. У птахів є крила.

Ці якості, або <dfn>властивості</dfn>, визначають чим є сам об'єкт. Зауважте, що схожі об'єкти мають однакові властивості, але їхні значення для кожного із об'єктів можуть відрізнятися. Наприклад, усі машини мають колеса, але не всі машини мають однакову їхню кількість.

Об'єкти JavaScript використовуються для моделювання об'єктів із реального світу, наділяючись такими ж як і їхні дійсні двійники властивостями і поведінкою. Ось приклад використання цієї ідеї для створення об'єкту `duck`:

```js
let duck = {
  name: "Aflac",
  numLegs: 2
};
```

Об'єкт `duck` має дві пари властивостей із значеннями: `name` із значенням `Aflac`, `numLegs` із значенням 2.

# --instructions--

Створіть об'єкт `dog` із властивостями `name` та `numLegs`, задавши їхні значення рядком символів та числом відповідно.

# --hints--

`dog` повинен бути об'єктом.

```js
assert(typeof dog === 'object');
```

`dog` повинен мати виражену рядком символів властивість `name`.

```js
assert(typeof dog.name === 'string');
```

`dog` повинен мати виражену числом властивість `numLegs`.

```js
assert(typeof dog.numLegs === 'number');
```

# --seed--

## --seed-contents--

```js
let dog = {

};
```

# --solutions--

```js
let dog = {
  name: '',
  numLegs: 4
};
```