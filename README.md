# routes-finder

### What this package does?

- This package finds all the API routes of an express application 

### How to use this package?

- Install the package and express library if you already have not installed it
`npm i routes-finder express`


- Create an express app object 
```js
const express = require('express');
const app = express();
```

- Require this package and call the `routesFinder` function by passing app object
```js
const { routesFinder } =  require('routes-finder');

routesFinder(app);
```

