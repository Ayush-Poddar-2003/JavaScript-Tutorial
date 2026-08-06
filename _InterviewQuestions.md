Question -

```js
for (var i = 1; i <= 3; i++) {}
console.log(i); //4
```

```js
for (let i = 1; i <= 3; i++) {}
console.log(i); //Error
```

```js
for (var i = 1; i <= 5; i++) {
  setTimeout(() => { 
    //makes i in the waiting, and is further used again
    console.log(i);
  }, 1000);
}
```

> setTimeout guarantees a minimum delay, not an exact execution time.

---

