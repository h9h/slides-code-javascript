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


---
# Deklarativ: Map

@gist[js](h9h/f241902cbdd8c10473f493c38653e12c)

---
# Noch deklarativer

```js
const squared = n => n * n

const result = [1, 2, 3].map(squared)

console.log(result)
``` 

