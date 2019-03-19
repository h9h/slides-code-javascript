---?image=assets/img/map-filter-magic.jpg

---
# Imperativ

```js
const array = [1, 2, 3]
const result = []

for (let i = 0; i < array.length; i++) {
  result.push(array[i] * array[i])
}

console.log(result)
```
@[1-2](Setup)
@[4,6](Loop)
@[5](die einzige Zeile mit Fachlichkeit)
@[1-6](wir sagen dem Computer, was er tun soll)


---
# @fa[code-branch](Deklarativ: Map)

```js
const squared = n => n * n

const result = [1, 2, 3].map(squared)

console.log(result)
``` 
@[3](hier steht genau **beschrieben**, was wir wollen!)
