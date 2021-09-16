# Easy APIs

## [Pokemon API](https://pokeapi.co/)

### Example

```js
fetch("https://pokeapi.co/api/v2/pokemon?limit=100&offset=200")
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```
