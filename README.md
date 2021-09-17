# Easy APIs to call from JavaScript

## Pokemon API

Documentation: https://pokeapi.co/

### Example - Fetch a list of Pokemons

```js
fetch("https://pokeapi.co/api/v2/pokemon?limit=10")
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```

## icanhazdadjoke

Documentation: https://icanhazdadjoke.com/api

### Example - Search for Dad Jokes

```js
fetch('https://icanhazdadjoke.com/search?page=1', {
  headers: { Accept: "application/json" },
})
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```
