# Easy APIs to call from JavaScript

## Bored API

Documentation: https://www.boredapi.com/

### Example - Fetch a random activity

```js
fetch("https://www.boredapi.com/api/activity")
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```

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

## Exchange Rates API

Documentation: https://www.exchangerate-api.com/docs

### Example - Find the latest currency exchange rates

```js
fetch('https://v6.exchangerate-api.com/v6/YOUR-API-KEY/latest/USD', {
  headers: { Accept: "application/json" },
})
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```

## NBA Matches API

Documentation: https://www.balldontlie.io/#introduction

### Example - Access statistical data from the NBA.

```js
fetch('https://www.balldontlie.io/api/v1/players', {
  headers: { Accept: "application/json" },
})
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```

## Genrenator API

Documentation: https://binaryjazz.us/genrenator-api/

### Example - Fetch a random genre or genre story.

```js
fetch('https://binaryjazz.us/wp-json/genrenator/v1/genre/', {
  headers: { Accept: "application/json" },
})
  .then((response) => {
    return response.json();
  })
  .then((json) => {
    console.log(json);
  });
```
